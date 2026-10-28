# Contributing

Thank you for considering a contribution. Issues, documentation improvements, bug reports, and code changes are all welcome.

## Before you start

- Search existing issues and pull requests to avoid duplicating work.
- For a substantial change, open an issue first to discuss the approach.
- Keep changes focused and explain the problem they solve.

## Set up the project

Use Python supported by your environment, then install the package and its runtime requirements:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .
python -m pip install -r requirements.txt
```

## Tests and changes

Run the relevant checks before opening a pull request. If the project has tests for the behavior you changed, run them with:

```bash
python -m pytest
```

Add or update tests when a code change alters behavior. Avoid committing generated data, model outputs, credentials, or other large or private files unless they are specifically required and safe to share.

## Pull requests

- Describe the motivation and summarize the change.
- Link related issues and note any limitations or follow-up work.
- Include test results, or explain why tests could not be run.
- Keep the pull request focused; maintainers may ask for revisions before merging.

By participating, you agree to follow the project's [Code of Conduct](CODE_OF_CONDUCT.md).
