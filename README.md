[![Build Status](https://travis-ci.com/bdwolfe/travis-ci-tutorial.svg?branch=master)](https://travis-ci.org/bdwolfe/travis-ci-tutorial)
[![Code Coverage](https://codecov.io/github/bdwolfe/travis-ci-tutorial/coverage.svg)](https://codecov.io/gh/bdwolfe/travis-ci-tutorial)

# travis-ci-tutorial
Just to learn how to use travis-ci in a java project! Modified from [Joao Neto's tutorial](https://github.com/joaomlneto/travis-ci-tutorial-java)

This is a working minimal example of how to use Travis CI (and Codecov) with Java on GitHub.

- It uses the [JUnit](https://junit.org) testing framework

# How To Start

1. [Fork](https://github.com/bdwolfe/travis-ci-tutorial/fork) this Repository
2. Make sure it is public (so we can get free CI!)
3. Fix the `README.md` badges (replacing all the `bdwolfe` occurrences in the file with `your-github-username`) and push the changes.
4. Go to [Travis CI](http://travis-ci.org) dot org (the .org is important!)
5. Sign in with your GitHub account
6. Under your profile settings, enable the repository
7. Make another edit to the repository (e.g., edit `README.md`) and push the changes. This should trigger a build in Travis CI.

## Code Coverage with CodeCov

This repository also integrates with Codecov to generate reports.

What's done for you:
- The [JaCoCo](https://www.jacoco.org) plugin is included in `pom.xml`
- On `.travis.yml`, `after_success` target executes the Codecov script.

What you need to do:
- Go to the Codecov website and create an account (or log in) with your GitHub account
- Add your repository (you can go there directly by going to https://codecov.io/gh/your-github-username/travis-ci-tutorial)
- Fix the `README.md` badge.
