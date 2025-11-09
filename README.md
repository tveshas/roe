# ROE - Multi-Platform Matrix Build

This repository demonstrates a GitHub Actions workflow with multi-platform matrix builds and artifact management.

## Features

- **Matrix Strategy**: Builds across multiple Node.js versions (14, 16, 18)
- **Parallel Execution**: All matrix jobs run simultaneously
- **Artifact Management**: Each build generates and uploads unique artifacts
- **Artifact Naming**: Artifacts follow the pattern `build-18ff4fd-node-<version>`

## Workflow

The workflow is located at `.github/workflows/matrix-build.yml` and includes:

- Matrix build strategy with 3 Node.js versions
- Artifact generation with build metadata
- Artifact upload using `actions/upload-artifact@v4`

## Contact

Email: 23f3001654@ds.study.iitm.ac.in

## License

MIT

