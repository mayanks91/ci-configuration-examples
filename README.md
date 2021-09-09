| **Azure<sup>&reg;</sup>&nbsp;DevOps** | **CircleCI<sup>&reg;</sup>** | **GitHub<sup>&reg;</sup>&nbsp;Actions** | **Travis&nbsp;CI&trade;** |
|:---------------------------|:-----------------:|:----------------------------:|--------------------------:|
| [![Build Status](https://dev.azure.com/iat-ci/ci-configuration-examples/_apis/build/status/mathworks.ci-configuration-examples)](https://dev.azure.com/iat-ci/ci-configuration-examples/_build) <br> ![Azure DevOps Coverage](https://img.shields.io/azure-devops/coverage/iat-ci/ci-configuration-examples/36) | [![CircleCI](https://circleci.com/gh/mathworks/ci-configuration-examples.svg?style=svg)](https://circleci.com/gh/mathworks/ci-configuration-examples) <br><br> | [![MATLAB](https://github.com/mathworks/ci-configuration-examples/actions/workflows/ci.yml/badge.svg)](https://github.com/mathworks/ci-configuration-examples/actions/workflows/ci.yml) <br><br> | [![Build Status](https://app.travis-ci.com/mathworks/ci-configuration-examples.svg)](https://app.travis-ci.com/mathworks/ci-configuration-examples) <br><br> |


# Continuous Integration (CI) usability repo for MATLAB<sup>&reg;</sup>


## About the code

The example MATLAB code example `dayofyear.m` is a simple function takes a date string `"mm/dd/yyyy"` and returns the day-of-year number.

Notes:
* MATLAB already includes a day-of-year calculation using `day(d,"dayofyear")`, where `d` is a datetime object. This code is only used as an example since it is a concept that is familiar to most people.
* The code coverage is intentionally set below 100% to show how missing coverage looks with badges. Uncomment the last test in `TestExamples.m` to increase the coverage to 100%.

There are 2 test classes provided:
1. TestExamples.m - A simple set of equality and negative tests
2. ParameterizedTestExamples.m - A set of 12 equality tests set up using the parameterized test format

The repository includes these files:

| **File Path**              | **Description** |
|:---------------------------|:----------------|
| [`code/dayofyear.m`](code/dayofyear.m) | The [`dayofyear`](code/dayofyear.m) function returns the day-of-year number for a given date string "mm/dd/yyyy" |
| [`tests/TestExamples.m`](tests/TestExamples.m) | The [`TestExamples`](tests/TestExamples.m) class provides a few equality and negative tests for the [`dayofyear`](code/dayofyear.m) function |
| [`tests/ParameterizedTestExample.m`](tests/ParameterizedTestExample.m) | The [`ParameterizedTestExample`](tests/ParameterizedTestExample.m) class provides 12 tests for the [`dayofyear`](code/dayofyear.m) function using the parameterized test format |

<br>


## Links
- [Continuous Integration with MATLAB and Simulink](https://www.mathworks.com/solutions/continuous-integration.html)

<br>
