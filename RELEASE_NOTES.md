# Release notes

## New in ScalaMock 3.4.2

- Scala 2.10, 2.11, 2.12 crossbuild
- log unepexcted calls after verifications were checked (removing an NPE)
- published to JCenter and Maven Central

## New in ScalaMock 3.4.1

- Scala 2.12 and 2.11 support

## New in ScalaMock 3.2.1

- [new feature] support for custom parameter matchers (issue #42)
- [new feature] named mocks (issue #82)
- [new feature] improved reporting of expectation errors (issue #82)
- [fix] mocking methods with default parameter value (issue #43)
- [fix] mocking polymorphic overloaded methods (issue #85)

## New in ScalaMock 3.2

- improved reporting of unsatisfied expectations (fix for #72)
- updated, extended and reorganized documentation (created the User Guide and Quick Start)
- improved support for sharing mocks and expectations by different test cases
- expectations can be set in Suite scope (fix for #25 and #35)
- fixed two bugs in scalamock-specs2-support:
  - mocks can be used in threads managed by thread pools (e.g. in Futures)
  - mocks can be defined in fixture-contexts
- improved support for mocking Java classes:
  - mocking overloaded methods in Java classes (fix for #34)
  - mocking Java classes with bridge methods (fix for #32)
  - mocking Java classes with polymorphic methods (fix for #24)
- various bug fixes:
  - mocks can be declared as `var` (fix for #62)
  - mocking methods with Seq[T] parameters (fix for #54)

## New in ScalaMock 3.1

- ScalaTest 2.0 support
- ScalaMock works with Scala-2.11

## New in ScalaMock 3.0.1

- Reinstate Specs2 support (fix for #26)
- Don't generate mocks for private methods (fix for #27)
