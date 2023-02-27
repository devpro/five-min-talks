---
theme: default
css: unocss
---

# Automated Testing 101

Auomating tests is one of the most important best practices of an organization developing and integrating components.

---

## Objectives

* Focus on the real added value
* Reduce the Time To Market
* Garantee the quality of service
* Ease and encourage updates
* Overcome IT complecity
* Enable technical improvement reworks

---

## Pyramid of Tests

![Pyramid of tests](https://martinfowler.com/articles/practical-test-pyramid/testPyramid.png)

---

## Challenges

* Create maintenable tests
* Identify a reproducible data set
* Enable non-developer contribution
* Have a comprehensive test plan
* Share test results
* Quickly investigate tests errors

---

## Good Practices

* Pipelines orchestrate the run of the tests
* Automated testing is fully integrated in development lifecycle
* Specifications follow an easy-to-read standard
* Strong collaboration between all actors
* Tools and processes must serve the people

---

## PageObject Pattern

![Page Objects, HTML Wrapper](https://www.martinfowler.com/bliki/images/pageObject/pageObject.png)

---

## BDD (Behavior driven development)

![Automated Tests, Executable Specifications, Living Documentation](https://i.imgur.com/Kpxju8c.png)

---

## Los 3 amigos

![Business, Testing, Development](https://dgage01.files.wordpress.com/2021/04/bdd-three-amigos.png)

---

## Gherkin language

```gherkin
Feature: Guess the word

  # The first example has two steps
  Scenario: Maker starts a game
    When the Maker starts a game
    Then the Maker waits for a Breaker to join

  # The second example has three steps
  Scenario: Breaker joins a game
    Given the Maker has started a game with the word "silky"
    When the Breaker joins the Maker's game
    Then the Breaker must guess a word with 5 characters
```

---

## Open-source tooling

* [Cucumber](https://cucumber.io/) ([GitHub org](https://github.com/cucumber))
* [Cypress](https://www.cypress.io/) ([docs](https://docs.cypress.io/), [sources](https://github.com/cypress-io/cypress) _★ 42.6k_)
* [Jest](https://jestjs.io/) ([docs](https://jestjs.io/docs/getting-started), [sources](https://github.com/facebook/jest) _★ 41.4k_)
* [Playwright](https://playwright.dev/) ([docs](https://playwright.dev/docs/intro), [sources](https://github.com/microsoft/playwright) _★ 47.7k_)
* [Selenium](https://www.selenium.dev/) ([docs](https://www.selenium.dev/documentation/), [sources](https://github.com/SeleniumHQ/selenium) _★ 25.8k_)
* [Taiko](https://taiko.dev/) ([sources](https://github.com/getgauge/taiko) _★ 3.2k_)
