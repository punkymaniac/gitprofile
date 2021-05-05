# gitprofile

A simple git profile management.

The usage of git is followed by the identity of the commiter/author.
This tools will help you to deal with multiple git identities.

## Feature
* Print current profile
* Save/add profile
* Change current profile with one saved profile
* List all profile saved
* Delete profile saved
* List all author/commiter profile on the project
* Change current profile with one author/commiter profile on the project
* All profiles are saved in a file: ~/.gitprofile

This repository contain also a pre-commit hook who allow to verify the profile before commiting.
This hook is usefull only on global hook or as default hook on each new repository.

## Getting Started

### Requirements
You need git to use gitprofile.

### Installing
Copy the script in your prefered $PATH folder location.
By example:
```
sudo cp gitprofile /usr/local/bin/gitprofile
```

### Recommanded configuration
Thinking usage as a git alias.
Configure the git alias with the following command:
```
git config --global alias.profile '!gitprofile'
```

