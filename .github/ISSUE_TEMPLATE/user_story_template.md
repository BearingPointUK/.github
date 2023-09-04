---
name: User Story template
about: A User Story to describes an issue or feature to be developed from the users perspective.
title: As a [WHO}, I want [WANT], so that [BUSINESS VALUE]
labels: User Story
assignees: ''

---
*Please complete each section and remove the instructions.*

# User Story

Please describe what you are trying to achieve in the form of a user story.
The user story should follow the following 

***As a [WHO}, I want [WANT], so that [BUSINESS VALUE].***

Where:

* WHO is the role or user persona who carries out the action. Try not to use "User"
* WANT is a description of what is desired or needed or the desired outcome or feature. The word "want" can replaced with "required", "need" or similar provided what is wanted is clear.
* BUSINESS VALUE describes the "why". The so-that clause of a story is important because understanding why a user wants what is described in the what portion of the story helps the team decide how best to implement the functionality.

The "so that" clause is option only if it adds no value. It almost all circumstances it should be present.

## INVEST

The user story must follow **INVEST** criteria:

* **I: Independent** As far as possible user stories should be independent on each other and able to be completed in any order. This a soft requirement as some stores will naturally depend on others, but this dependency will be obvious.
* **N: Negotiable** The scope of the story should be able to variable and negotiable with the developers. i.e. there should be many way to satisfy the story.
* **V: Valuable** The story must have a clear and quantifiable value to the business. This can be specified informally as high/medium/low and should impact multiple layerrs in the system.
* **E: Estimable** The user story must be concrete enough allow the developers to estimate it. It must not be an open ended requirement.
* **S: Small** The story must be small, enough that a version if it can be completed within a single sprint iteration. Larger stories must be split into smaller ones.
* **T: Testable** The business should be able to describe the tests required that will validate the sort has been completed. See the [Acceptance Tests](#acceptance-tests) and [Examples](#examples) section below.

# Acceptance Tests

*Please provide a set of acceptance tests or rules that the user story should follow.*

For example, if the user story realted to logging in then the acceptance tests might be:

* Passwords must be alphanumeric only (no punctuation)
* Passwords must be at least 15 characters long
* Passwords must include at least 5 digits
* Passowrds must include at least 5 UPPER case characters

# Examples

*Please provide several examples of the acceptance criteria.*

For example taking the password rules above the examples might be:

* "abcde12345ABCDE" - valid at least 15 chars, 5 digits, 5 uppercase
* "ABC12345ABCDE" - invalid, too short no lower case letters
* "!"£$%ABCDEF123456" - invalid contains punctuation

## Checklist

- [ ] The user story meets all of the **INVEST** criteria
- [ ] The user story has acceptance tests
- [ ] The user story has examples
- [ ] User Story has a label assigned to it
