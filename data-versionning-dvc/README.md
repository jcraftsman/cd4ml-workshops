# Data versionning with dvc

## Objectives

The goal of this example is to give you some hands-on experience with a basic machine learning version control scenario: working with multiple versions of datasets and ML models using DVC commands.
By doing this hands-on, you will learn to use dvc to:

- Fetch and store large files on an external storage outside of the source control repository
- Keep track of those files' versions, allowing us to retrain our models when the data changes
- Keep track of the dependency graph and commands used to execute the ML pipeline, allowing the process to be reproduced in other environments
- Integrate with Git branches to allow multiple experiments to co-exist

## Duration

 :alarm_clock: 1 hour

## Instructions

### Step 0: Install Prerequisites

#### dvc

Follow the installation steps described [here](https://dvc.org/doc/install).

#### git

You will also need [git](https://git-scm.com/) obviously.🤷‍♂️

## Useful tutorials/links

- <https://dvc.org/doc/tutorials/versioning>
- <https://dvc.org/doc/get-started>
- <https://dvc.org/doc/command-reference/remote/add>
