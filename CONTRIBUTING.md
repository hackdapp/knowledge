# Contributing

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

## Getting Started

Install required global dependencies:

```bash
npm install -g yarn
```

Check out the code and go into the kapian.io directory:

```bash
git clone https://github.com/hackdapp/kapian.io.git
cd kapian.io
```

Install the dependencies and bootstrap the monorepo:

```bash
yarn
```

## Running Docs

All the documentation can be found in the root level `docs` directory. Running
the following command will stand up the docs server which will watch for
changes.

```bash
yarn docs:serve
```

## Conventional Commits

Lerna depends on the use of the [Conventional Commits Specification](https://conventionalcommits.org/)
to determine the version bump and generate CHANGELOG.md files. Make sure your
commits and the title of your PRs follow the spec. A pre-commit hook and CI test
have been added to further enforce this requirement.

## Tips for Getting Your Pull Request Accepted

1. Make sure all new features are tested and the tests pass.
2. Bug fixes must include a test case demonstrating the error that it fixes.
3. Open an issue first and seek advice for your change before submitting
   a pull request. Large features which have never been discussed are
   unlikely to be accepted. **You have been warned.**
