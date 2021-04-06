## Release Automation Playground

This is a temporary repo to experiment with release automation.

The goal is to refine the release automation process before implementing it in the [parse-server](https://github.com/parse-community/parse-server) repository. This is part of the effort to implement [fixed release cycles](https://github.com/parse-community/parse-server/issues/7271).

The expected outcomes are:
- Definition of new GitHub labels
- Definition of new forward looking branch structure to collect breaking changes to the next major release and allow for preleases
- Definition of new changelog design for auto-update compatibility

The current focus is on using [semantic-release](https://github.com/semantic-release/semantic-release) as release automator.
