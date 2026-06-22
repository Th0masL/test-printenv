# test-printenv

Sandbox for capturing CI/CD environment variables.

A single job dumps the runner's `GIT*`/`CI*` environment for whatever event
fired (branch push, tag, release, manual run), on **GitHub Actions**
([`.github/workflows/printenv.yml`](.github/workflows/printenv.yml)),
**GitLab CI** ([`.gitlab-ci.yml`](.gitlab-ci.yml)), and
**CircleCI** ([`.circleci/config.yml`](.circleci/config.yml)).

## Repositories

The same project lives on both platforms so each CI can run:

- GitHub: <https://github.com/Th0masL/test-printenv>
- GitLab: <https://gitlab.com/Th0masL/test-printenv>

