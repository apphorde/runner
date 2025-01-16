# Design/ideas

## Triggers

- OOB WebHooks
  - receive from GitHub/GitLab
- platform-independent API call

## Queue

- Tasks go to a queue, but they need to run in the same runner as their dependencies

## type: CronJob

- env variables
- Any executable command

## type: Job

- Workspace
- Stages

## type: Image

- env variables
- image
- args

## Task

- inputs (read env vars, read cli options, files)
- output artifacts
- output state
- one task pipes into another
- expose a request/response interface to leverage platform API's

