---
name: Job Story template
about: A Job Story to describes an issue or feature to be developed, when the outcome is more important than the user who performs the action.
title: When [SITUATION], I want to [MOTIVATION] so I can [EXPECTED OUTCOME]
labels: job story
assignees: ''

---
*Please complete each section and remove the instructions.*

# Job Story

Please describe what you are trying to achieve in the form of a job story.

A job story *may* be preferable to an user story if the user who carries out the action is not distinct.
In these cases the expected outcome is *likely* to be more important than the user who might carry out the action.

A Job story *may* also be more preferable if the story describes a machine to machine interaction that is triggered by an event
In this case the "I" in the story should be replaced by a hostname.

A job story an always be rewritten into a User Story and vice versa.

The job story should follow the following format: 

***When [SITUATION], I want to [MOTIVATION] so I can [EXPECTED OUTCOME].***

Where:

* SITUATION is a description of the context when the job story applies. (or of what event has occurred).
* MOTIVATION is a description of what the user wants. Think of this as the users goal.
* EXPECTED OUTCOME describes what the uses expects to see as a result. Think of this as the "why" 

More details:

[Mike Cohn Website](https://www.mountaingoatsoftware.com/blog/job-stories-offer-a-viable-alternative-to-user-stories)
[Alan Klement who coined the idea](https://www.intercom.com/blog/using-job-stories-design-features-ui-ux/) [and](https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27)   

## INVEST

The job stories must still follow **INVEST** criteria:

* **I: Independent** As far as possible user stories should be independent on each other and able to be completed in any order. This a soft requirement as some stores will naturally depend on others, but this dependency will be obvious.
* **N: Negotiable** The scope of the story should be able to variable and negotiable with the developers. i.e. there should be many way to satisfy the story.
* **V: Valuable** The story must have a clear and quantifiable value to the business. This can be specified informally as high/medium/low and should impact multiple layerrs in the system.
* **E: Estimable** The user story must be concrete enough allow the developers to estimate it. It must not be an open ended requirement.
* **S: Small** The story must be small, enough that a version if it can be completed within a single sprint iteration. Larger stories must be split into smaller ones.
* **T: Testable** The business should be able to describe the tests required that will validate the sort has been completed. See the [Acceptance Tests](#acceptance-tests) and [Examples](#examples) section below.

# Acceptance Tests

*Please provide a set of acceptance tests or rules that the user story should follow.*

For example, if the job story realted to logging in then the acceptance tests might be:

* Passwords must be alphanumeric only (no punctuation)
* Passwords must be at least 15 characters long
* Passwords must include at least 5 digits
* Passwords must include at least 5 UPPER case characters

# Examples

*Please provide several examples of the acceptance criteria.*

For example taking the password rules above the examples might be:

* "abcde12345ABCDE" - valid at least 15 chars, 5 digits, 5 uppercase
* "ABC12345ABCDE" - invalid, too short no lower case letters
* "!"£$%ABCDEF123456" - invalid contains punctuation

## Checklist

- [ ] The job story meets all of the **INVEST** criteria
- [ ] The job story has acceptance tests
- [ ] The job story has examples
- [ ] Job Story has a label assigned to it
