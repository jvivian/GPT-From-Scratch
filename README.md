# GPT-From-Scratch

[![Release](https://img.shields.io/github/v/release/jvivian/GPT-From-Scratch)](https://img.shields.io/github/v/release/jvivian/GPT-From-Scratch)
[![Build status](https://img.shields.io/github/actions/workflow/status/jvivian/GPT-From-Scratch/main.yml?branch=main)](https://github.com/jvivian/GPT-From-Scratch/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/jvivian/GPT-From-Scratch/branch/main/graph/badge.svg)](https://codecov.io/gh/jvivian/GPT-From-Scratch)
[![Commit activity](https://img.shields.io/github/commit-activity/m/jvivian/GPT-From-Scratch)](https://img.shields.io/github/commit-activity/m/jvivian/GPT-From-Scratch)
[![License](https://img.shields.io/github/license/jvivian/GPT-From-Scratch)](https://img.shields.io/github/license/jvivian/GPT-From-Scratch)

Repository for learning about Attention/Transformer architecture by building one from scratch

- **Github repository**: <https://github.com/jvivian/GPT-From-Scratch/>
- **Documentation** <https://jvivian.github.io/GPT-From-Scratch/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

``` bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:jvivian/GPT-From-Scratch.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with 

```bash
make install
```

You are now ready to start development on your project! The CI/CD
pipeline will be triggered when you open a pull request, merge to main,
or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/codecov/).

## Releasing a new version



---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).