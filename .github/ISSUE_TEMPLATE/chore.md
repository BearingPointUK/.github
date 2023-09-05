---
name: Chore template
about: A chore is a task that adds no direct business value but requires effort to do.
title: Chore Title
labels: chore
assignees: ''

---
*Please complete each section and remove the instructions.*
*Chores should not be used for security fixes, including dependency updates.. Please use a security fix issue for those.*

A chore can be one of:

A spike - to learn and provide information that is needed to estimate another story.
Something to improve developer efficiency i.e. shorten the cycle time, remove repetitive tasks etc.
Something related to the infrastructure or a change to the infrastructure. Please also all an "infrastructure" label in this case. 
Changes due to an external constraint e.g. support a change in an external web serive that we rely on.
Some sort of "pre-work" that is common to multiple other stories, which provides no value but acts as an enabler

See [The Carbonfive blog](https://blog.carbonfive.com/what-are-these-chores-doing-in-my-backlog/).

**Note: We use specific issue types for security changes. These should not be chores.**

# What needs to be done?

Please describe what needs to be done.

# Why is this required?

Please describe why this chore is required.

# What happens if this chore does is not completed?

Please describe what might happen if this chore is delayed or never completed

# What are the acceptance criteria?

Please describe how we know that this task has been completed. This could be a change in a tests status, or a new test, or
confirmig that the system still works as expected.

In the case of an infrastructure change please try to describe a test case which will indicate if the required infrastructure
is either in place or has been changed as we expect.