# Repo: action-tests

## This repo is used to explore GitHub actions

### Repo File Organization

- module-a
  - pom.xml
- module-b
  - pom.xml

### Goals: develop GitHub Actions to:

- create a branch named according to the following pattern: 'release-x.x'
- create a feature branch named according to the following pattern: '{jira repo}-{issue number}-uptick-{version}'
  - check out feature branch
  - find and replace the current version with a new version
  - commit/push changes to feature branch
  - confirm Pull Request was created correctly
