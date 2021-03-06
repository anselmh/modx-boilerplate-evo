# How to contribute

I like to encourage you to contribute to the reopsitory. 
This should be as easy as possible for you but there are a few things to consider when contributing.
The following guidelines for contribution should be followed if you want to submit a patch.

## How to prepare

* You need to have a [GitHub account](https://github.com/signup/free)
* Submit an [issue ticket](https://github.com/anselmh/modx-boilerplate-evo/issues) for your issue if the is no one yet.
  * Describe the issue and include steps to reproduce when it's a bug.
  * Ensure to mention the earliest version that you know is affected.
* Fork the repository on GitHub

## Make Changes

* In your forked repository, create a topic branch for your upcoming patch.
  * Usually this is the master branch.
  * Create a branch based on master; `git branch
    fix/master/my_contribution master` then checkout the new branch with `git
    checkout fix/master/my_contribution`.  Please avoid working directly on the
    `master` branch.
* Make commits of logical units and describe them properly.
* Check for unnecessary whitespace with `git diff --check` before committing.

* If possible, submit tests to your patch / new feature so it can be testes easily.
* Assure nothing is broken by running all the tests.

## Submit Changes

* Push your changes to a topic branch in your fork of the repository.
* Open a pull request to the original repository (mine) and choos ethe right original branch you want to patch.
* If not done in commit messages (which you really should do) please reference and update your issue with the code changes.
* Even if you have write access to the repository, do not directly push or merge pull-requests. Let an other team member review your pull-request and approve. 

# Additional Resources

* [General GitHub documentation](http://help.github.com/)
* [GitHub pull request documentation](http://help.github.com/send-pull-requests/)
