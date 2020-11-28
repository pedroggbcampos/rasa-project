# Meal Planner
> The Meal Planner is a digital voice assistant based on Rasa that helps you with the everyday tasks such as buying ingredients, preparing meals and finding recipes.

## Table of contents
* [General info](#general-info)
* [Git workflow](#git-workflow)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)

## General info
The repository was initialized with the base code of Rasa's default startup project.

## Git workflow
Feature branch workflow
1. Clone project:
```
$ git clone git@example.com:project-name.git
```
2. Create branch with your feature:
```
$ git checkout -b $feature_name
```
3. Write code and then stage all tracked, modified files before the commit:
```
$ git add *
```
4. Commit changes:
```
$ git commit -m "Add x feature and correct file y"
```
5. Push your branch:
```
$ git push origin $feature_name
```
6. Review your code on commits page.

7. Create a merge request.

8. Your team lead will review the code & merge it to the main branch.

9. If project is not finished, go back to step 2.

## Technologies
* Python - version 3.7.9
* Rasa - version 2.1.1

## Setup (Linux)
If you want to use with conda which is recommended, firstly install miniconda. See the [miniconda install instructions](https://docs.conda.io/en/latest/miniconda.html)
```
$ conda create -n rasa-lab python=3.7
$ pip install rasa
$ rasa --version
$ rasa init
```

## Features
List of ready features:
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

To-do list:
* Wow improvement to be done 1
* Wow improvement to be done 2

## Status
Project is: _in progress_
