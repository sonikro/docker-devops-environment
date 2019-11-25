# Docker Devops Environment

Sometimes we want a local instance of some applications, in order to run tests.
This repository is here to store a list of well-known applications, and its docker-compose file, so we can get started in no time.

## Usage
Just open the folder of the correspondent application, and run **docker-compose up -d**
Example:

```bash
cd atlassian 
docker-compose up -d
```
You should have Jira, Bitbucket and Confluence running with a PostgreSQL Database, with only this single command.
