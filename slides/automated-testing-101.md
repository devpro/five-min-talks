---
theme: seriph
highlighter: shiki
lineNumbers: false
css: unocss
transition: slide-left
---

# Automated Testing 101

Want to know about one of the most important best practices in software development?

---

# Objectives

What can be achieved through test automation?

- 🎯 **Focus** on the real added value
- 🚀 **Reduce** the Time To Market
- 🛎 **Guarantee** the quality of service
- 💪 **Overcome** IT complecity
- 👷 **Enable** technical improvement reworks

---

# Pyramid of Tests

<img src="/images/pyramid-test.png" alt="pyramid of tests" width="800"/>

---

## Challenges

What is difficult to have with test automation?

- **Maintenable** tests
- **Reproducible** data set
- **Inclusive** solution with contributions from non-technical people
- **Straightforward** test plan
- **Comprehensive** test results
- **Investigable** Errors

---

## Good Practices

- Pipelines orchestrate the run of the tests
- Automated testing is fully integrated in development lifecycle
- Specifications follow an easy-to-read standard
- Strong collaboration between all actors
- Tools and processes must serve the people

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

- [**Cucumber**](https://cucumber.io/) ([GitHub org](https://github.com/cucumber))
- [**Cypress**](https://www.cypress.io/) ([code](https://github.com/cypress-io/cypress) _★ 42.6k_)
- [**Jest**](https://jestjs.io/) ([code](https://github.com/facebook/jest) _★ 41.4k_)
- [**Playwright**](https://playwright.dev/) ([code](https://github.com/microsoft/playwright) _★ 47.7k_)
- [**Selenium**](https://www.selenium.dev/) ([code](https://github.com/SeleniumHQ/selenium) _★ 25.8k_)
- [**Taiko**](https://taiko.dev/) ([code](https://github.com/getgauge/taiko) _★ 3.2k_)
