# Session 16 - CI/CD with GitHub Actions

Practice repository for the Session 16 assignment of
[devops-heros](https://github.com/Ishan007-bot/devops-heros/tree/main/session-16-github-actions).

| Workflow | File | Trigger |
| :--- | :--- | :--- |
| Hello GitHub Actions | `.github/workflows/hello-actions.yml` | manual |
| Workflow Demo | `.github/workflows/workflow-demo.yml` | manual |
| Jobs and Steps Demo | `.github/workflows/jobs-steps.yml` | manual |
| Runner Demo | `.github/workflows/runner-demo.yml` | manual |
| Secrets Demo | `.github/workflows/secrets-demo.yml` | manual (needs `DEMO_SECRET`) |
| Artifact Demo | `.github/workflows/artifact-demo.yml` | manual |
| Build and Test Pipeline | `.github/workflows/build-and-test.yml` | push / PR to `main` touching `09-build-and-test/`, manual |
| Final CI Pipeline | `.github/workflows/final-ci.yml` | push / PR to `main` touching `10-final-cicd-pipeline/`, manual |
