# NodeJS-API-cleanArchtecture

libs used in project:

```bash
# installing liter plugin standard as development dependence
# is similary eslint configurations, stablishing development standardizations
# is not necessary create any external doc to set your code pattern
$ npm install standard -D

# use this command to see standard notifications about format errors
$ npx standard

# ---------------------------------------------------------------------------------------------------------------------
# installing lint-staged as development dependence
# allows you to run scripts at git staged area
#
# ex: use case about lint-staged: format code pattern using lib standard when commit is effected.
# "lint-staged": {
#   "*.js": [
#     "standard"
#   ]
# },
# using flag --fix, the standard lib will try to fix all files with bad format using git add as script
$ npm install lint-staged -D

# use this commands to process all stardard commands
$ npx lint-staged

# ---------------------------------------------------------------------------------------------------------------------
# installing husk as development dependece
# allows you to set hooks to set "pre-commit", running a script (lint-staged) before any commit to fix any code format
# this lib enable any commit file with bad format
$ npm install huks
```
