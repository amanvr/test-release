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
# New cycle test
# Final test
# Test RC increment Thu 16 Apr 2026 09:50:01 BST
# Another fix Thu 16 Apr 2026 09:53:24 BST
# New cycle test Thu 16 Apr 2026 09:58:46 BST
# No cleanup test Thu 16 Apr 2026 11:36:50 BST
# E2E Test 1 Thu 16 Apr 2026 11:53:05 BST
# E2E Test 2 - should fail Thu 16 Apr 2026 11:55:50 BST
