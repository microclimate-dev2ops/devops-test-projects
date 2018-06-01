# devops-test-projects

Several projects exist here that are used by the Devops component of Microclimate only.

These do *not* represent exemplar sample projects and should not be used except as part of the tests for Microclimate.

Specifically, the test projects provided here are as follows, and, as of the 1st of June 2018, these are all based on the demo projects under the [microclimate-demo](https://github.com/microclimate-demo) organisation.

Under the `microprofile` folder there are multiple branches, including `master`.
- `tester`: this is a different branch with a unique Git commit message provided
- `named-image`: the Jenkinsfile will name the built image `microprofile-testing-testing`
- `oops`: (has intentional failures so it won't deploy successfully

These test projects are used to ensure certain Devops APIs function as expected: the tests will import the projects, deploy the applications, and the APIs should correctly report on their statuses and details.

