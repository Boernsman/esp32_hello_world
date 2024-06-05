# Github Workflow

## Triggering Events:

* The workflow triggers on pushes to the main branch and branches matching feature/*.
* The workflow also triggers on pull requests targeting the main branch.

## Jobs:

* The workflow runs on the ubuntu-latest runner.

## Steps:

* Checkout code: Uses the actions/checkout action to clone the repository.
* Build the project: Sets the target to ESP32 and builds the project using idf.py.
