# SAPTeam's Magisk module template
This magis module template made the module creation way easier.

## Features
- Automates the build and releasing with Github actions.
- Easily initiates the module properties with setup.py.
- Has a biult in installer script, so you don't need to write a installer script.

## Getting started
Working with this template is very easy. Most of actions is automated. with this instruction you can benefit all features of this module:
- First you need to make a fork of this repository to your account.
- Then clone your new repository to your computer.
- in module files open `setup.py` with an text editor and replace the variables with your module props.
- Run `setup.py` and after after finishing the first run, delete it.
- Open `module.prop` and `update.json` to correct the github account and repo name if it was wrong.
- Put your module files and update the changelog.
- Create a tag and push it. when a new tag is pushed the action is triggered and new release zip is automatically created.
You must check the Actions tab of your project for checking issues.

Note: for using magisk 14.0+ update api you need to update the version string in `update.json` in every releases.

## Credits
This module forked from [MMT-Extended](https://github.com/Zackptg5/MMT-Extended) template.
