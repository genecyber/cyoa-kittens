## [cyoa-kittens](../page-0/README.md) >> Page 42 Chapter 2

```
You dodge to the left and fall into a jungle of acceptance tests...
```

```
The basics ...
- putting in the framework takes time
- but ... 1 or 2 acceptance test later, there is some more clarity around the state of the application from a higher-level perspective (I mean, non-coders can see the test run and pass and see their value)
- if all of those tests pass, though, what is the benefit?
  - domain language
  - all on the same page
  - act as regression
  - owners can see state and value
  - tests are in code
  - faster feedback loops
 
Test Cases that should be in this branch (cucumber/selenium tests):
NOTE that these were written for the Runicorn game, but ideas may apply to Kittens as well

- Background:
    Given I am on the Runicorn homepage

  Scenario: Gameplay is started on a new game
    Given the start game button is active
    And the restart button is inactive
    When I click start game
    Then the game starts

  Scenario: Gameplay is restarted on a finished game
    Given the start game button is inactive
    And the restart game is active
    When I click restart ganme
    Then the game starts 

Notes on choices:
- Yay! We see value in high level tests and our test strategy is sound; let's add new features
- We're on a roll! Let's add a bunch more acceptance tests!

```

If you choose Add a new feature using BDD: [turn to page 8](../page-8/README.md)

If you choose More Acceptance Tests: [turn to page 17](../page-17/README.md)
