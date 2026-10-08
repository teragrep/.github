## Description

<!-- Please include a summary of changes made in your pull request. -->

<!-- If you can't fill all check boxes in Checklists section, please explain why. -->

## Checklists

<!-- Fill check boxes before submitting the pull request. -->

### General

- [ ] I have checked that the project has a README file and it's up to date.
- [ ] I have checked my code does not contain FIXME or TODO comments.

### Code Quality

- [ ] I have checked that my code follows metrics set in Procedure: Class Metrics.
- [ ] I have checked that my code follows metrics set in Procedure: Method Metrics.
- [ ] I have checked that my code follows metrics set in Procedure: Object Quality.
- [ ] I have checked that my code does not have any NULL values.
- [ ] I have described objects at interface level with Javadoc.

### Testing

#### General

- [ ] I have checked that my test files and functions have meaningful names.
- [ ] I have checked that each test tests only a single behavior.
- [ ] I have done happy tests.
- [ ] I have tested only my own code.
- [ ] I have tested at least all public methods.
- [ ] I have checked that my tests are not (partially) commented out.

#### Assertions

- [ ] I have checked that my tests use assertions and not runtime overhead.
- [ ] I have checked that my tests end in assertions.
- [ ] I have checked that there is no comparison statements in assertions.
- [ ] I have checked that assertions are in tests and not in helper functions.
- [ ] I have checked that assertions for iterables are outside of for loops and both sides of the iteration blocks.
- [ ] I have checked that assertions are not tested inside consumers.
- [ ] I have checked that hand-crafted variables in assertions are used accordingly.

#### Testing Data

- [ ] I have tested algorithms and anything else with the possibility of unbound growth.
- [ ] I have checked that all testing data is local and fully replaceable or reproducible or both.
- [ ] I have checked that all test files are standalone.
- [ ] I have checked that all test-specific fake objects and classes are in the test directory.
- [ ] I have checked that my tests do not contain anything related to customers, infrastructure or users.
- [ ] I have checked that my tests do not contain non-generic information.
- [ ] I have checked that my tests do not do external requests and are not privately or publicly routable.

#### Statements

- [ ] I have checked that my tests do not use throws for exceptions.
- [ ] I have checked that my tests do not use try-catch statements.
- [ ] I have checked that my tests do not use if-else statements.

#### Java

- [ ] I have checked that my tests for Java uses JUnit library.
- [ ] I have checked that my tests for Java uses JUnit utilities for parameters.

#### Other

- [ ] I have only tested public behavior and not private implementation details.
- [ ] I have tested [Object Equality](https://docs.oracle.com/javase/6/docs/api/java/lang/Object.html#equals%28java.lang.Object%29).
- [ ] I have checked that I do not have any manual tests or I have a valid reason for them and I have explained it in the PR description.
