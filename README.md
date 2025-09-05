A demo monorepo powered by proto and moon with different python versions across the projects:
- one for the pre-commit library for the whole workspace
- one for the snake-lib sub-project

Issues
- I failed to use [moon's hook system](https://moonrepo.dev/docs/guides/vcs-hooks) to run the [pre-commit](https://pre-commit.com) tool for the [commit-msg](https://git-scm.com/docs/githooks#_commit_msg) phase.
I would like to run the https://github.com/alessandrojcm/commitlint-pre-commit-hook hook to check the commit message format, other tools rely on them (like [python-semantic-release](https://python-semantic-release.readthedocs.io/en/latest/) for python, but similar tools exist for other languages to generate release tags and notes)
