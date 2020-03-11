# Project Management

## Backlog
- ignore hidden directories for most recent file display in open project
- C-c C-t binding for lisp testing (all)
  - via hook or via projectile? => both work, hook is fine at the time
- C-c C-c t for test at point
- add proj-run-interpreter-on-side to open an interpreter
- refactor functions for them to be namespace compliant
- Refactor mock-files so that it stays in test scope
- separate tools from proj code


## Done
+ Git the project
#### use second latest file to always display 2 files ####

  + change get-rel-file test to account for this
  + update get-rel-file so it does the job
#### Shortcut for tdd
+ have a shortcut to save, eval and test at point just like elpy
+ have a shortcut to run all tests



## Larger Backlog
- emacs should autosave correctly
  - done as a minor mode?
  - version history?
	- conflicts with git