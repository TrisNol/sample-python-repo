[![GitHub license](https://img.shields.io/github/license/TrisNol/sample-python-repo.svg)](https://github.com/TrisNol/sample-python-repo/blob/master/LICENSE)
[![Github all releases](https://img.shields.io/github/downloads/TrisNol/sample-python-repo/total.svg)](https://github.com/users/TrisNol/packages/container/package/sample-python-repo)
[![GitHub forks](https://img.shields.io/github/forks/TrisNol/sample-python-repo.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/TrisNol/sample-python-repo)
# Sample Python Repo
This repo contains a skeleton for Python projects containing some basic DevOps´ components like CI/CD pipelines.

## Linting
The code of this repo will be linted with [PyLint](https://pylint.org/) automatically on each push and pull-request to ensure that the files are correctly formatted in order to improve readability.

## Tests
You can add your tests in the test/ directory. By providing the prefix test_ the files will be recognized and executed by PyTest.

## Documentation
The documentation is created with the help of [MkDocs Material](https://squidfunk.github.io/mkdocs-material/), which generates html-based docs that is exposed via GitHub pages. In order to see the documentation, some configuration in GitHub needs to be done. Head to the repo´s settings and enable GitHub pages. Set the source to branch `gh-pages`. The documentation should now be hosted at `http[s]:<username>.github.io/<repo-name>`

In order to adapt the config, change the specifics in `mkdocs.yml`.
To manually build the documentation execute the following command:`mkdocs build`.
However, the documentation will be built automatically on each push and added to the repo by a GitHub Action - so you don´t have to generate it yourself each time.