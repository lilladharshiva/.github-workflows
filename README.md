### 🔄 CI/CD Workflows

This repository uses **GitHub Actions** for automated testing and deployment:

- **`.github/workflows/ci.yml`**: Automatically runs on every push and pull request to `main`.
  - Runs code formatting checks and linting (`npm run lint`).
  - Executes unit test suites (`npm test`).
  - Builds the production distribution (`npm run build`).
