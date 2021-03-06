:warning: App no longer active :warning:

**Consider the code in this repo as sample code.**

:warning: Some dependencies in the Gemfile point to versions which have security vulnerabilities. Please update to the latest versions before using this code. :warning:

# CTA Aggregator Docs
Documentation for the cta-aggregator project

This repo uses [slate](https://github.com/lord/slate) to allow markdown-driven
documentation.  

The codebase for the CTA Aggregator is located here: https://github.com/RagtagOpen/cta-aggregator.

This docs site is deployed at https://ragtagopen.github.io/cta-aggregator-docs/.

## Setup

To run this project locally, install the dependencies and launch the server. To do this.
* In your terminal, at the root of this project, run `bundle install`.
* Once the dependencies have been installed, run `bundle exec middleman server`.
* In your browser, navigate to `http://localhost:4567`.

## Deployments

There's a deployment script at the root of this project.  We do not currently
have a  way to automate updates to the documentation site.  So, after your
changes have been accepted and merged into master, you'll need to
pull the changes down to your local master branch and then run the deploy script.

* In your terminal, get on your master branch and make sure it's up to date with the remote.
* Run `bash deploy.sh`.
* In your browser, navigate [here](https://ragtagopen.github.io/cta-aggregator-docs) and verify that everyhing looks correct.


## To Do
* Show examples of what happens when user attempts to create duplicate record
* Show examples of what happens when user attempts to provide malformed request
