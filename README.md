# debugit-attack-test

A test repository for the security tests of GitHub Runner Monitor: https://github.com/amir-bialek/Github-Runner-Monitor

GitHub Runner Monitor's Debug it feature opens draft fix pull requests only in repositories whose main branch is protected by a ruleset.
This repository's main branch has that ruleset: every change needs a pull request with 2 approvals, and no one can bypass it.
The security tests open a draft fix pull request here, then check that Debug it cannot push to main or merge it.
Each test run closes its pull request and deletes its branch afterwards.

It holds no code and is not meant to be used.
