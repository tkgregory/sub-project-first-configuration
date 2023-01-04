This repository is an example to go along with the article 
at [tomgregory.com](https://tomgregory.com/gradle-evaluation-order-for-multi-project-builds).

## Running

Demonstrates using `evaluationDependsOnChildren()` to evaluate a 
project's sub-projects first, during the configuration phase of the 
build:

`./gradlew doThing1 doThing2`
