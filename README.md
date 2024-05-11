# simple-python-app-pr-check-v4

This repo is based on the simple-python-app-github-actions-v3 template. Simple-python-app-pr-check-v4 adds a pull request check (and a branch protection) so that only changes that can be built before merging is possible to merge.

It's a powerful way to ensure the main branch is always buildable. Pull request checks are not only limited to checking for build issues, but can also include test, code coverage, security checks. Basically anything we find valueable to 
check for before merging to our protected branches. Typically main and/or release branches are good candidates for being configured as protected branches.

This line is only in the demo-pr-check-passing branch. The purpose is to demo that when this change is pushed, a PR check is executed and if successful the PR can be merged. 

![GitHub Actions status](https://github.com/hvl71/simple-python-app-pr-check-v4/actions/workflows/docker-publish.yml/badge.svg)


