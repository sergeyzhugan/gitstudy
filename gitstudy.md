# Git

## Initialization

`git init`

## Good commit name

**what(where):make**

what:
- feat
- test
- build
- refactor
- fix

refactor(element): rename parameter x

## Configuration

    git config [user.name](http://user.name) "vasia"
    git config [user.email](http://user.name) "vasia@ukr.net"
    
    cat .git/config
    
    git config --global [user.name](http://user.name) "vasia"
    git config --global [user.email](http://user.name) "vasia@ukr.net"
    
    git config --list
    git config --list —global
    
    git config --unset user.name
    git config --unset user.email
    
    git config --remove-section user
