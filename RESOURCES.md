# Jenkins Resources

## Knowledge

- [Jenkins Pipeline documentation](https://www.jenkins.io/doc/book/pipeline/)
  Core source for Pipeline concepts, including Pipeline, agent/node, stage, and step. Use for: mental models and pipeline structure.
- [Using a Jenkinsfile](https://www.jenkins.io/doc/book/pipeline/jenkinsfile/)
  Official guide to storing pipelines as code in source control. Use for: writing beginner-to-intermediate `Jenkinsfile` examples.
- [Getting started with Pipeline](https://www.jenkins.io/doc/book/pipeline/getting-started/)
  Official guide for creating Pipeline projects in Jenkins, including the classic UI flow and the `Pipeline script from SCM` option. Use for: connecting a Jenkins job to a repository-hosted `Jenkinsfile`.
- [Running Pipelines](https://www.jenkins.io/doc/book/pipeline/running-pipelines/)
  Official guide for running, rerunning, and restarting Pipeline builds. Use for: understanding completed Pipeline runs, stage restarts, and run-level troubleshooting entry points.
- [Pipeline Syntax reference](https://www.jenkins.io/doc/book/pipeline/syntax/)
  Detailed Declarative Pipeline syntax reference. Use for: checking exact syntax when adding new directives.
- [Pipeline Steps reference](https://www.jenkins.io/doc/pipeline/steps/)
  Searchable reference for available Pipeline steps from Jenkins plugins. Use for: finding steps such as `sh`, `junit`, `archiveArtifacts`, and `checkout`.
- [Pipeline `sh` step reference](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#sh-shell-script)
  Official reference for the shell step. Use for: understanding that a script with a nonzero exit status normally fails the step, unless options such as `returnStatus` are used.
- [Installing Jenkins](https://www.jenkins.io/doc/book/installing/)
  Official installation entry point. Use for: choosing a local Jenkins installation route when the lessons move from reading pipelines to running them.
- [Installing Jenkins with Docker](https://www.jenkins.io/doc/book/installing/docker/)
  Official Docker installation guide. Use for: running a local Jenkins controller, opening `http://localhost:8080`, reading Docker logs, and finding the initial admin password.
- [Using Jenkins agents](https://www.jenkins.io/doc/book/using/using-agents/)
  Official explanation of controller/agent execution architecture. Use for: understanding where pipeline work actually runs.

## Wisdom (Communities)

- [Jenkins community forums](https://community.jenkins.io/)
  Official community discussion space. Use for: real-world troubleshooting, best-practice questions, and learning from Jenkins practitioners.
- [Jenkins issue tracker](https://issues.jenkins.io/)
  Public tracker for Jenkins core and plugin issues. Use for: checking whether odd behavior is a known bug after you can describe the symptom precisely.
