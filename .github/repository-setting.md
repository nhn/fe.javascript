# Repository Settings

## Restrict editing to collaborators only
Setting Tab > Options(default) > Features

- [x] Wikis  
- [ ] Restrict editing to collaborators only
- [x] Issues
- [x] Project

## Enable squash merge only
Setting Tab > Options(default) > Merge button

- [ ] Allow merge commits  
- [x] Allow squash merging  
- [ ] Allow rebase merging 

## Protect Default Branches from Merge
Setting Tab > Branches > Protected branches > Choose a branch.. Dropdown

### Master, Support branch
- [x] Protect this branch
    - [x] Require pull request reviews before merging
        - [ ] Dismiss stale pull request approvals when new commits are pushed
    - [x] Require status checks to pass before merging
        - [ ] Require branches to be up to date before merging
    - [x] Include administrators

### Develop, develop
- [x] Protect this branch
    - [x] Require pull request reviews before merging
        - [ ] Dismiss stale pull request approvals when new commits are pushed
    - [x] Require status checks to pass before merging
        - [ ] Require branches to be up to date before merging
    - [ ] Include administrators
