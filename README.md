# simple-python-app-pr-check-v4

This repo is based on the simple-python-app-github-actions-v3 template. Simple-python-app-pr-check-v4 adds a pull request check (and a branch protection) so that only changes that can be built before merging is possible to merge.

It's a powerful way to ensure the main branch is always buildable. Pull request checks are not only limited to checking for build issues, but can also include test, code coverage, security checks. Basically anything we find valueable to 
check for before merging to our main branch.

![GitHub Actions status](https://github.com/hvl71/simple-python-app-pr-check-v4/actions/workflows/docker-publish.yml/badge.svg)


