# Table of contents: rcc documentation
## 1 [Incomplete list of rcc use cases](https://github.com/robocorp/rcc/blob/master/docs/usecases.md#incomplete-list-of-rcc-use-cases)
### 1.1 [What is available from conda-forge?](https://github.com/robocorp/rcc/blob/master/docs/usecases.md#what-is-available-from-conda-forge)
## 2 [Incomplete list of rcc features](https://github.com/robocorp/rcc/blob/master/docs/features.md#incomplete-list-of-rcc-features)
## 3 [Tips, tricks, and recipies](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#tips-tricks-and-recipies)
### 3.1 [How to see dependency changes?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-see-dependency-changes)
#### 3.1.1 [Why is this important?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#why-is-this-important)
#### 3.1.2 [Example of dependencies listing from holotree environment](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#example-of-dependencies-listing-from-holotree-environment)
### 3.2 [How to freeze dependencies?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-freeze-dependencies)
#### 3.2.1 [Steps](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#steps)
#### 3.2.2 [Limitations](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#limitations)
### 3.3 [How pass arguments to robot from CLI?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-pass-arguments-to-robot-from-cli)
#### 3.3.1 [Example robot.yaml with scripting task](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#example-robotyaml-with-scripting-task)
#### 3.3.2 [Run it with `--` separator.](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#run-it-with----separator)
### 3.4 [How to run any command inside robot environment?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-run-any-command-inside-robot-environment)
#### 3.4.1 [Some example commands](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#some-example-commands)
### 3.5 [How to convert existing python project to rcc?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-convert-existing-python-project-to-rcc)
#### 3.5.1 [Basic workflow to get it up and running](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#basic-workflow-to-get-it-up-and-running)
#### 3.5.2 [What next?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-next)
### 3.6 [Is rcc limited to Python and Robot Framework?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#is-rcc-limited-to-python-and-robot-framework)
#### 3.6.1 [This is what we are going to do ...](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#this-is-what-we-are-going-to-do-)
#### 3.6.2 [Write a robot.yaml](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#write-a-robotyaml)
#### 3.6.3 [Write a conda.yaml](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#write-a-condayaml)
#### 3.6.4 [Write a bin/builder.sh](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#write-a-bin-buildersh)
### 3.7 [Think what you can do with this conda.yaml?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#think-what-you-can-do-with-this-condayaml)
### 3.8 [How to control holotree environments?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-control-holotree-environments)
#### 3.8.1 [How to get understanding on holotree?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-get-understanding-on-holotree)
#### 3.8.2 [How to activate holotree environment?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-activate-holotree-environment)
### 3.9 [What is shared holotree?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-shared-holotree)
### 3.10 [How to setup rcc to use shared holotree?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-setup-rcc-to-use-shared-holotree)
#### 3.10.1 [One time setup](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#one-time-setup)
#### 3.10.2 [Per user initialization](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#per-user-initialization)
#### 3.10.3 [Reverting back to private holotrees](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#reverting-back-to-private-holotrees)
### 3.11 [What can be controlled using environment variables?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-can-be-controlled-using-environment-variables)
### 3.12 [How to troubleshoot rcc setup and robots?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#how-to-troubleshoot-rcc-setup-and-robots)
#### 3.12.1 [Additional debugging options](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#additional-debugging-options)
### 3.13 [What is in `robot.yaml`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-in-robotyaml)
#### 3.13.1 [Example](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#example)
#### 3.13.2 [What is this `robot.yaml` thing?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-this-robotyaml-thing)
#### 3.13.3 [What are `tasks:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-tasks)
#### 3.13.4 [What are `devTasks:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-devtasks)
#### 3.13.5 [What is `condaConfigFile:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-condaconfigfile)
#### 3.13.6 [What are `environmentConfigs:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-environmentconfigs)
#### 3.13.7 [What are `preRunScripts:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-prerunscripts)
#### 3.13.8 [What is `artifactsDir:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-artifactsdir)
#### 3.13.9 [What are `ignoreFiles:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-ignorefiles)
#### 3.13.10 [What are `PATH:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-path)
#### 3.13.11 [What are `PYTHONPATH:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-pythonpath)
### 3.14 [What is in `conda.yaml`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-in-condayaml)
#### 3.14.1 [Example](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#example)
#### 3.14.2 [What is this `conda.yaml` thing?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-is-this-condayaml-thing)
#### 3.14.3 [What are `channels:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-channels)
#### 3.14.4 [What are `dependencies:`?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-dependencies)
#### 3.14.5 [What are `rccPostInstall:` scripts?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-are-rccpostinstall-scripts)
### 3.15 [Where can I find updates for rcc?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#where-can-i-find-updates-for-rcc)
### 3.16 [What has changed on rcc?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#what-has-changed-on-rcc)
#### 3.16.1 [See changelog from git repo ...](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#see-changelog-from-git-repo-)
#### 3.16.2 [See that from your version of rcc directly ...](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#see-that-from-your-version-of-rcc-directly-)
### 3.17 [Can I see these tips as web page?](https://github.com/robocorp/rcc/blob/master/docs/recipes.md#can-i-see-these-tips-as-web-page)
## 4 [Profile Configuration](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#profile-configuration)
### 4.1 [What is profile?](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#what-is-profile)
#### 4.1.1 [When do you need profiles?](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#when-do-you-need-profiles)
#### 4.1.2 [What does it contain?](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#what-does-it-contain)
### 4.2 [Quick start guide](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#quick-start-guide)
### 4.3 [What is needed?](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#what-is-needed)
### 4.4 [Discovery process](https://github.com/robocorp/rcc/blob/master/docs/profile_configuration.md#discovery-process)
### 4.5 [What is execution environment isolation and caching?](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#what-is-execution-environment-isolation-and-caching)
### 4.6 [The second evolution of environment management in RCC](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#the-second-evolution-of-environment-management-in-rcc)
#### 4.6.1 [Relocation and file locking](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#relocation-and-file-locking)
### 4.7 [A better analogy: accommodations](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#a-better-analogy-accommodations)
#### 4.7.1 ["I invited you to my home."](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#i-invited-you-to-my-home)
#### 4.7.2 ["Welcome to a hotel built out of ship containers."](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#welcome-to-a-hotel-built-out-of-ship-containers)
#### 4.7.3 ["Welcome to an actual Hotel."](https://github.com/robocorp/rcc/blob/master/docs/environment-caching.md#welcome-to-an-actual-hotel)
## 5 [rcc -- how to build it](https://github.com/robocorp/rcc/blob/master/docs/BUILD.md#rcc----how-to-build-it)
### 5.1 [Tooling](https://github.com/robocorp/rcc/blob/master/docs/BUILD.md#tooling)
### 5.2 [Commands](https://github.com/robocorp/rcc/blob/master/docs/BUILD.md#commands)
### 5.3 [Where to start reading code?](https://github.com/robocorp/rcc/blob/master/docs/BUILD.md#where-to-start-reading-code)