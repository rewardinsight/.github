# Contributing guidelines 

The following is a set of guidelines for contributing to Reward's repositories. 
Please help future developers by keeping our codebases clean.


## Pull requests
Consider the following before making a pull request:

### ❕ First and foremost
- [ ] Is this a breaking change? If so, have I considered the implications?

### 🖊 My PR
- [ ] Have I referenced my ticket number in the title?
- [ ] Does my branch number contain the ticket number?
- [ ] Has the description been filled out?
- [ ] If it's not ready for review - have I added 'WIP' (work in progress) to my title to prevent it being accidentally merged?

 ### ✅ Clean code
- [ ] Have I performed a self-review of my code (including spellchecking)?
- [ ] Does my code follow Reward's [coding standards](https://rewardinsight.atlassian.net/wiki/spaces/SD/pages/2190671996/Coding+Standards)?
- [ ] Do any database changes follow Postgres' [best practices](https://rewardinsight.atlassian.net/wiki/spaces/HYD/pages/17044516/Postgres+Best+Practices)?
- [ ] Have I linted my code?
- [ ] Have I added comments to my code? (particularly in order to explain complexities I've added)

### 🤗 Good practices
- [ ] Have I confirmed that packages/dependencies in this repo are up to date?
- [ ] Have I have added appropriate logging to provide traceability of my code?
- [ ] Have I have ensured that environment variables are correctly referenced (for all environments)?

### 🎉 Well tested

- [ ] Have I tested locally (or where appropriate) to prove my code works?
- [ ] Do any new and/or existing unit tests pass locally?
- [ ] Have I confirmed that my changes don't generate new warnings?
