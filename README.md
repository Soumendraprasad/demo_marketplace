# GoCodeo-CLI

Action to install and configure GoCodeo CLI.

This action enables you to run GoCodeo CLI commands as part of your workflow.


## Inputs

### `path` (Required)
- **Description:** Path of the folder on which to generate test cases `.ts` files inside that folder.

### `branch` (Required)
- **Description:** Specifies the branch on which the pull request is made.

### `PAT` (Required)
- **Description:** Personal Access Token (PAT) used for authentication purposes.

### `EMAIL` (Required)
- **Description:** Email ID linked with the repository.

### `NAME` (Required)
- **Description:** Git username.

### `secret` (Required)
- **Description:** GoCodeo Key used for authentication and authorization.
