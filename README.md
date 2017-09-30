## [cyoa-kittens](../page-0/README.md) >> Page 23 Chapter 2

```
The basics ...
- after 1 rainbow of effort
- developers have learned about unit tests
- a unit testing framework has been added
- a couple of unit tests have been written
  - Unit tests to consider
    - stuff in onImageClick in main.js
- the unit tests that were written don't even begin to cover the large function that does most of the work
- design flaws are identified; take care of that now? Or ...

Notes:
- codebase has some design that will not be scalable
- a couple of unit tests cover very little functionality within one function
- adding test framework from scratch takes time, learning new testing paradigms take time
- 1 rainbow of effort didn't get you much benefit, but does make progress toward needed tests

Code that should go in here:
- 1 or two unit tests against the onImageClick in main.js
- framework is mocha/chai

Choices:
- refactor the application, given the design flaw that has been identified
  - break down the one function into many and begin to have clearer coverage
- keep going down unit tests path
  - leave the large function and just werite a bunch more unit tests for it
- Unit tests are cool, and now let's focus on acceptance tests
```

If you choose Refactor: [turn to page 13](../page-13/README.md)

If you choose Double Down on Unit Tests: [turn to page 74](../page-74/README.md)

If you choose begin to focus on Acceptance Tests, [turn to page 17](../page-17/README.md)
