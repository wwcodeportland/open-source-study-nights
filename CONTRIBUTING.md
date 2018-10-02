# Contributing to Open Source Study Nights
👍 🎉 First off, thanks for taking the time to contribute! 🎉 👍

The following is a set of guidelines for contributing to our repo. These are just guidelines, not rules - use your best judgment and feel free to propose changes to this document in a pull request.

### Issues
Issues are created here. If you'd like to look for any issues that we need help with, start here!

### Pull Requests
Pull Requests are the way concrete changes are made to the code, documentation, dependencies, and tools contained in the wwcodeportland/open-source-study-nights repository. We're open to both code changes and documentation changes.

##### Step 1: Fork
Fork the project on GitHub and clone your fork locally.

```
$ git clone git@github.com:username/requests.git
  $ cd requests
  $ git remote add upstream https://github.com/wwcodeportland/open-source-study-nights.git
  $ git fetch upstream
```

##### Step 2: Branch
To keep your development environment organized, create local branches to hold your work. These should be branched directly off of the master branch.

```
$ git checkout -b my-branch -t upstream/master
```

##### Step 3: Test
Make sure that you test your code to ensure that it works. If you're adding a new feature or fixing a bug, please consider writing a unit test!

##### Step 4: Format
Run `npm run-script` prior to commiting your changes, to make sure that all of the new code is formatted properly.

##### Step 5: Commit
Try to keep your changes grouped logically within individual commits. There is no limit to the number of commits in a pull request. A good commit message should describe what changed and why.

```
$ git add my/changed/files
  $ git commit
```

### Questions?
If you have any questions about contributing, please feel free to submit a new issue.
