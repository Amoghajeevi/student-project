# DevOps CI/CD Pipeline Project

This project demonstrates a basic CI/CD pipeline using **GitHub Actions** for a Node.js project.

---

## Workflow File

Location: `.github/workflows/ci-cd-pipeline.yml`

### What It Does:
- Triggers on every push to the `main` branch.
- Runs on Ubuntu GitHub-hosted runner.
- Steps included:
  -  Checkout the code
  -  Set up Node.js (v20)
  -  Install dependencies with `npm install`
  -  Run tests using `npm test` (configured to use Jest)

---

##  Success

The CI/CD pipeline now works as expected. Tests pass and workflow runs succeed.

GitHub Repo: [https://github.com/Amoghajeevi/student-project](https://github.com/Amoghajeevi/student-project)
