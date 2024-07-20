### It performs below operations for NODE projects. 
- Setup Node version.
- NPM build.
- Static code analysis using either lint or sonar.
- Execute unittests.
- Store artifact. Artifact name pattern: `<repo-name>-<branch-name>-<build-number>`

### Input parameters are:
- node_version: NodeJS version.  Default is `18.20.3`
- static_code_analysis: Tool to be used for static code analysis like sonar, lint. Default is `lint`
- build: Pass true if build action needs to be performed.
- unit_test: Pass true if unit test action needs to be performed.
- code_analysis: Pass true if static code analysis action needs to be performed.
- store_artifact: Pass true to store the artifacts.

Default value will be `false` if the parameter is not passed.