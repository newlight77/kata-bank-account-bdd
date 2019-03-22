# Kata-Bank-Account-ATDD

[![Build Status](https://travis-ci.org/newlight77/kata-bank-account-bdd.svg?branch=master)](https://travis-ci.org/newlight77/kata-bank-account-bdd)
[![Maintainability](https://api.codeclimate.com/v1/badges/5215148bf0b74c26470a/maintainability)](https://codeclimate.com/github/newlight77/kata-bank-account-bdd/maintainability)
[![codecov](https://codecov.io/gh/newlight77/kata-bank-account-bdd/branch/master/graph/badge.svg)](https://codecov.io/gh/newlight77/kata-bank-account-bdd)
[![BetterCodeHub compliance](https://bettercodehub.com/edge/badge/newlight77/kata-bank-account-bdd?branch=master)](https://bettercodehub.com/)

## Kata Statement

Bank Account kata for practice TDD implemented by [Jorge Sánchez (Xurxodev)](https://github.com/xurxodev/Bank-Account-Kata/blob/master/README.md)

Think of your personal bank account experience

When in doubt, go for the simplest solution

### Requirements

These are requirements for kata.

#### Initial requirements

* Deposit (negative not permitted)
* Withdrawal (negative not permitted)  
* GetBalance  
* Account statement (date, quantity, balance) 
* Statement printing 

#### Extra requirements if you feel with force :)

* Deposit and Withdrawal (EUR and USD)

## My Approach

### Technical stack 

I'm using Springboot, Java and Cucumber. 

From the original statement, I decided to add account creation feature.

### Story Mapping

Let's translate the features above into user stories :

* US1 : Create an account
* US2 : Do not allow non-resident of France to create an account 
* US3 : Deposit (negative not permitted)
* US4 : Withdrawal (negative not permitted)  
* US5 : GetBalance  
* US6 : Account statement (date, quantity, balance) 
* US7 : Statement printing

## Run it

```bash
./mvnw clean test
```

