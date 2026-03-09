# agentd-github-template

This is a template for creating a new project that will be run using the [agentd](https://github.com/geoffjay/agentd)
project.

## Otterfile

```
VAR GITHUB_USER=geoffjay
VAR GITHUB_REPO=supercalifragilisticexpialidocious
VAR GITHUB_PROJECT_ID=1234

LAYER https://github.com/otter-layers/agentd-github-template \
  TARGET .agentd/ \
  TEMPLATE github_user=${GITHUB_USER} github_repo=${GITHUB_REPO} github_project_id=${GITHUB_PROJECT_ID}
```
