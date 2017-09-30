## [cyoa-kittens](../page-0/README.md) >> [Page 42 Chapter 2](../page-42/README.md) >> Page 8 Chapter 3

```
While writing your feature using BDD
```

```
The basics:
- New feature is added, using BDD, so there are cucumber/acceptance tests covering it
- One of the tests for this exposes a bug that was not previously identified
- with no unit tests and large function, difficult to debug
- highlight high level of coverage with acceptance tests, but no unit tests

Specifics:
- New feature should be:
  - Page title should change based on whose turn it is
- Acceptance test(s) for it should be:
  - Scenario: On user turn, title shows user
    Given a game is being played
    When it is the User's Turn
    Then the page title displays Turn: User
    And the content area also displays Turn: User

  - Scenario: On computer turn, title shows computer
    Given a game is being played
    When it is the Computer's Turn
    Then the page title displays Turn: Computer
    And the content area also displays Turn: Computer

- Bug identified should be:
  - Main content area for Turn should have always said User
  

```
[you were eaten by a Grue](https://en.wikipedia.org/wiki/Grue_(monster))


___just kidding: Use the above line if you want the user to die___

The end

To try again: [turn to page 42](../page-42/README.md)

