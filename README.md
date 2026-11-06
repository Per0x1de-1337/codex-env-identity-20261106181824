# Disposable Actions environment-identity fixture

This tester-owned public repository compares GitHub Actions environment object
resolution across potentially ambiguous names. Every environment contains only
a unique synthetic marker. Workflow logs emit SHA-256 digests, never a real
secret or deployment credential.

