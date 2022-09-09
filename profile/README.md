# asoltd

## Ongoing projects

- [Premiere](https://github.com/premiere-sh)
- [DAP](https://github.com/piotrostr/dap)

## Interview list

Roles available:

- Frontend
  - [Next.js](https://nextjs.org/) ([React](https://reactjs.org/))
- Backend
  - [FastAPI](https://fastapi.tiangolo.com/) (Python)
  - [gin-gonic](https://github.com/gin-gonic/gin) (Go)
- Solidity
  - [hardhat](https://hardhat.org/) (Solidity and TypeScript)

For all of the roles one needs to know how to write tests and be familiar with
testing, as we will be using CI/CD.

At first I will be writing out test-cases, translating the business
requirements from the stakeholders (Yoni mainly lol) and suggesting implementation
details.

If you have done leetcode questions or codewars katas, you should be familiar
with the process already.

There will be frontend testing as well (using
[Cypress](https://go.cypress.io/get-started)), our aim should be to achieve
100% coverage. That means, every line of code (or in case of frontend - every
feature) is covered by a unit-test. Especially for backend stuff and most
definitely for Solidity smart-contracts. As you may know, after deploying the
contract it is immutable,
so the shame is eternal.

## Frameworks

- Frontend

  - [Jest](https://jestjs.io/) for unit-tests
  - Cypress for e2e testing

- Backend

  - [pytest](https://docs.pytest.org/en/7.1.x/contents.html) for Python
    (built-in `unittest` module will also work as pytest
    picks up both)
  - built-in gotest framework for Go

- Solidity
  - [Mocha](https://mochajs.org/) with the [Hardhat goodies](https://hardhat.org/tutorial/testing-contracts)

## Commit Conventions Cheatsheet

* feat: (new feature for the user, not a new feature for build script)
* fix: (bug fix for the user, not a fix to a build script)
* docs: (changes to the documentation)
* style: (formatting, missing semi colons, etc; no production code change)
* refactor: (refactoring production code, eg. renaming a variable)
* test: (adding missing tests, refactoring tests; no production code change)
* chore: (updating grunt tasks etc; no production code change)

## Book yourself a slot

For the following two weeks (June 27th - July 10th) I will be running the
interviews for ASO LTD, there will be projects starting as soon as possible.

**[My Calendar](https://calendly.com/piotr-ostrowski/30min)**
