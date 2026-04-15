# test-release

Test project for debugging release-please workflows.

## Quickstart

```bash
pip install -e .
hello
```

## Workflows

- **cicd.yaml** - Runs on push to main, handles release-please
- **deploy.yml** - Triggered after release, deploys to PyPI
- **promote-to-stable.yaml** - Promotes RC to stable release
# Test RC increment
