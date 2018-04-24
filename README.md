# Purpose

This repo saves useful tooling configurations for Salesforce development.

You are warmly welcomed to send pull request.

# Content

## dx-skeleton folder

With several default configuration built-in when initiate scratch-org.

1. define configurations in `project-scratch-def.json`, such as using `enterprise edition`, locale as `US` (language in English), enable community and API, disable browser cache.
2. use [editorconfig](http://editorconfig.org/) to support consistant cross platform file saving format.
3. use `.gitignore` to ignore unnessariy file types for git

## pmd-rules folder

This folder saves PMD rules that I consider good to use in real project.

[PMD](https://pmd.github.io) is a code analyzer tool that supports Apex language.

It is recommended to run it in CI with pre-defined rules to assure better code quality.
