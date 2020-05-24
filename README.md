# embedded-workspace

## What to demonstrate....

Our goal is to improve code quality. This repository demonstrates how we can leverage tools to help us do this.
Tighten the feedback loop - get feedback early and often.

Tools we'll discuss?
* clang tidy
* clang format
* valgrind
* code coverage
* continuous integration (CI)
* Sanitizers

Concepts to talk about
* Find bugs early, save time later
* Making wrong code look wrong (an argument for formatters) (saves time)

How to get started
* Sandboxes - make new code clean, prioritize warnings for old code
* Configuring builds for google test (embedded example)
* Living in two worlds (embedded build, UT build)
* Refactoring code for test, what makes code testable what does not
* Plug xunit patterns
* CI jobs
* Valgrind results
* Plug smart pointers
* Coverage

What's else?
* TDD
* Tighten feedback loops in other activities - Requirements, Design, QA, and so on.
