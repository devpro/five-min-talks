---
theme: seriph
highlighter: shiki
lineNumbers: false
css: unocss
transition: slide-left
title: Automated Testing 101
---

# Automated Testing 101

Want to know about one of the most important best practices in software development?

---

# Objectives

What can be achieved with the right approach?

- 🎯 **Focus** on the real added value
- 🚀 **Reduce** the Time To Market
- 🛎 **Guarantee** the quality of service
- 💪 **Overcome** IT complexity
- 👷 **Enable** technical improvement reworks

---

# Pyramid of Tests

Foundation of any testing strategy

<img src="/images/pyramid-test.png" alt="pyramid of tests" class="m-8 ml-30 h-80 rounded shadow" />

---

# Challenges

What is difficult to have with test automation?

- ⛑ **Maintenable** tests
- 🏬 **Reproducible** data set
- ✍ **Inclusive** solution with contributions from non-technical people
- 🧪 **Straightforward** test plan
- 📖 **Comprehensive** test results
- 🐛 **Investigable** errors

---

# Lessons learned

Known recipes to succeed

- Tests are executed in a neutral environment (automation pipelines)
- Development and testing of any change are done at the same time
- Specifications are accessible and explicit
- Best practices and patterns are followed while engineering the solution
- Any failure in production is a perfect candidate for test automation
- Focus is made on the most used and critical usecases

---

# PageObject Pattern

Split the code between the application features and the UI components

<img src="https://www.martinfowler.com/bliki/images/pageObject/pageObject.png" alt="Page Objects, HTML Wrapper" class="m-8 ml-50 h-80 rounded shadow" />

---

# BDD (Behavior driven development)

An Agile software development process that encourages collaboration

<img src="/images/bdd.png" alt="Automated Tests, Executable Specifications, Living Documentation" class="m-8 ml-60 h-80 rounded shadow" />

---

# Los 3 amigos

Business, Testing, Development

<img src="/images/los-3-amigos.jpg" alt="Los 3 Amigos" class="ml-70 h-100 rounded shadow" />

---

## Gherkin language

Describe any process in simple words

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

Available tooling

- [**Cucumber**](https://cucumber.io/) ([GitHub org](https://github.com/cucumber))
- [**Cypress**](https://www.cypress.io/) ([code](https://github.com/cypress-io/cypress) _★ 42.6k_)
- [**Jest**](https://jestjs.io/) ([code](https://github.com/facebook/jest) _★ 41.4k_)
- [**Playwright**](https://playwright.dev/) ([code](https://github.com/microsoft/playwright) _★ 47.7k_)
- [**Selenium**](https://www.selenium.dev/) ([code](https://github.com/SeleniumHQ/selenium) _★ 25.8k_)
- [**Taiko**](https://taiko.dev/) ([code](https://github.com/getgauge/taiko) _★ 3.2k_)
