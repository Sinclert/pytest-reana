# Changelog

## [0.95.0](https://github.com/Sinclert/pytest-reana/compare/v0.9.2...0.95.0) (2024-05-07)


### Code refactoring

* **docs:** move from reST to Markdown ([#123](https://github.com/Sinclert/pytest-reana/issues/123)) ([4710f11](https://github.com/Sinclert/pytest-reana/commit/4710f1195557c5e1ae1a993084f26010e035f822))


### Continuous integration

* **actions:** update GitHub actions due to Node 16 deprecation ([#129](https://github.com/Sinclert/pytest-reana/issues/129)) ([8710f89](https://github.com/Sinclert/pytest-reana/commit/8710f8923d00096205d228a8d71b86f161e66141))
* added flake8 linter ([23a4d0d](https://github.com/Sinclert/pytest-reana/commit/23a4d0ddd1419ac3a5290aedcc0ddbaa37ae5e23))
* added github actions workflow ([19650cb](https://github.com/Sinclert/pytest-reana/commit/19650cb477f55e9f8751d46ca49bc2ae33226dca))
* added python 2.7 to github action python test strategy ([b73728b](https://github.com/Sinclert/pytest-reana/commit/b73728bfbebdd080ca914038162d26e8eacaf1e9)), closes [#73](https://github.com/Sinclert/pytest-reana/issues/73)
* **commitlint:** addition of commit message linter ([#118](https://github.com/Sinclert/pytest-reana/issues/118)) ([67259a6](https://github.com/Sinclert/pytest-reana/commit/67259a6c33413c84b53528413b88556b9cd2fb5d))
* **commitlint:** allow release commit style ([#125](https://github.com/Sinclert/pytest-reana/issues/125)) ([bfee7a4](https://github.com/Sinclert/pytest-reana/commit/bfee7a43c22771a8c3a39df81307029d1c6975f1))
* **commitlint:** check for the presence of concrete PR number ([#122](https://github.com/Sinclert/pytest-reana/issues/122)) ([7cb6926](https://github.com/Sinclert/pytest-reana/commit/7cb69260b2b4bfbcdf1de02b64fbc180db67fb81))
* pin ubuntu version in GA jobs ([8f244ac](https://github.com/Sinclert/pytest-reana/commit/8f244ac227bc03116cd540e82dd04b18eac23a58))
* **release-please:** initial configuration ([#118](https://github.com/Sinclert/pytest-reana/issues/118)) ([b87d9e9](https://github.com/Sinclert/pytest-reana/commit/b87d9e973a35ae00bc76422fc39f444dea36a8ae))
* **shellcheck:** check all shell scripts recursively ([#121](https://github.com/Sinclert/pytest-reana/issues/121)) ([4ba7548](https://github.com/Sinclert/pytest-reana/commit/4ba754893b5b20981413c812464e8171d6eebe29))
* **shellcheck:** fix exit code propagation ([#122](https://github.com/Sinclert/pytest-reana/issues/122)) ([fd232e6](https://github.com/Sinclert/pytest-reana/commit/fd232e6f1da0cd714755629376b8f0947597a387))
* update all actions ([eb61bb2](https://github.com/Sinclert/pytest-reana/commit/eb61bb20e7e6a1f1b67c4d9aee7f71c9cab982fa))
* use Python 3.12 stable release ([c3733c7](https://github.com/Sinclert/pytest-reana/commit/c3733c706438607ebb6b642034a9dce4267c27f0))


### Documentation

* add .readthedocs.yaml to migrate to RTD v2 ([661ea1c](https://github.com/Sinclert/pytest-reana/commit/661ea1c6c3ca10c1bd2198d333814d49fd314735))
* add fixture usage docs and plug sphinx ([ad66108](https://github.com/Sinclert/pytest-reana/commit/ad66108df630b65756162753fc1daae7b79e0dff))
* **authors:** complete list of contributors ([#124](https://github.com/Sinclert/pytest-reana/issues/124)) ([39c0238](https://github.com/Sinclert/pytest-reana/commit/39c0238b453c570e7d451669a53c63c7cf351650))
* fix kombu version and docstrings for classes ([6967964](https://github.com/Sinclert/pytest-reana/commit/6967964a65e9b41ec9a7764e7632a8c967451e68))
* fix rtfd build badge so it shows the real status ([d20d1c3](https://github.com/Sinclert/pytest-reana/commit/d20d1c3479c14976f78728bbbb9b9aaab7a9a31d))
* new inter-sphinx location for Celery docs ([08e55be](https://github.com/Sinclert/pytest-reana/commit/08e55be4e61e6db6ac0035b886aaff20dd606462))
* REANA-Pytest-Commons camelcase ([634bdc0](https://github.com/Sinclert/pytest-reana/commit/634bdc0f34a9510751fb2db593acb90b777b52ff))
* set default language to English ([567bf1b](https://github.com/Sinclert/pytest-reana/commit/567bf1b6f41ebcd74772ff41646a105dad211843))
* single-page RTFD outline ([d5ce477](https://github.com/Sinclert/pytest-reana/commit/d5ce477eeae09cc2c91f0a5816204d37fc8170f1))
* standard badge list and order ([8106da2](https://github.com/Sinclert/pytest-reana/commit/8106da2eca9f2e47985a1d5831f9c17aee164ec3))
* waffle -&gt; github projects ([8771479](https://github.com/Sinclert/pytest-reana/commit/8771479bdc7b51c598d24b9b10a28ca62fbd3e05))


### Chores

* **master:** release 0.95.0a1 ([408888f](https://github.com/Sinclert/pytest-reana/commit/408888f301e9f2514c284f79ab3e342be93ec2db))

## 0.9.2 (2023-11-30)

- Changes CI to use the stable release of Python 3.12.

## 0.9.1 (2023-09-26)

- Adds support for Python 3.12.
- Changes `apispec` dependency version in order to be compatible with `PyYAML` v6.
- Fixes container image fixtures to be Podman-compatible.
- Fixes Kombu documentation linking.

## 0.9.0 (2022-12-13)

- Adds fixture providing example of user secrets needed for Kerberos tests.
- Adds support for Python 3.11.
- Fixes location of Celery docs for ReadTheDocs pages.
- Removes hard-dependency on `black` code formatter version.

## 0.8.1 (2022-01-05)

- Adds support for Python 3.10.

## 0.8.0 (2021-11-22)

- Adds nested Yadage workflow specification fixture.
- Adds empty workflow workspaces for sample workflows by default.
- Adds internal representation of a scatter-gather Snakemake workflow fixture.
- Changes `tmp_shared_volume_path` fixture to be configurable through environment variable.
- Changes fixtures to run with the full workspace path stored in the database.
- Removes support for Python 2.

## 0.7.2 (2021-07-02)

- Changes internal dependencies to remove click.

## 0.7.1 (2021-03-17)

- Adds support for Python 3.9.
- Fixes minor code warnings.
- Fixes installation by upgrading REANA-DB version.

## 0.7.0 (2020-10-20)

- Adds new `__reana` database schema for `db` fixture.
- Fixes a problem related to duplicated database session.
- Changes code formatting to respect `black` coding style.
- Changes documentation to single-page layout.

## 0.6.0 (2019-12-19)

- Adds fixtures for secrets store.
- Centralises test requirements.
- Adds Python 3.8 support.

## 0.5.0 (2019-04-16)

- Makes workspace path configurable for the `sample_workflow_workspace`
  fixture through the `path` parameter.
- Adds `sample_serial_workflow_in_db` fixture.
- Exposes previously hidden `sample_yadage_workflow_in_db` fixture.
- Adds missing database session close in `session` fixture.
- Adds helpers to represent starting and requeueing job conditions,
  `sample_condition_for_starting_queued_workflows` and
  `sample_condition_for_requeueing_workflows`.

## 0.4.1 (2018-11-06)

- Adds directory including sample workspace data.

## 0.4.0 (2018-11-06)

- Initial public release.
