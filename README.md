# GITS

Shell application to manage multiple git repositories from its parent folders. 

## Installation
- Export ```gits``` to path

## Usage

Go to parent directory of all the git repos.
```
gits status
gits pull --rebase
```

## Requirements
- Needs GNU Parallel installed
- ```brew install parallel``` for Mac OSX

## Working
Execute all commands parallely. For example, executing ```gits pull --rebase``` from the parent directory of all the git repositories will parallely pull your code in all repositories.
