# ci-smoke-lab-e2e
Throwaway sandbox to prove the contribution + CI loop works end to end

## Build artifact

This repository's CI pipeline (`.github/workflows/ci.yml`, triggered on demand via `workflow_dispatch`) writes a short `demo-build.txt` file and uploads it as a build artifact named exactly **demo-build**.

- Artifact name: `demo-build`
- Uploaded by: CI workflow job `build` on `ubuntu-latest`
- Smoke check: the CI job writes the artifact and GitHub Actions uploads it as `demo-build`, proving the contribution + CI loop works end to end.
