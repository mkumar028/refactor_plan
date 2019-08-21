# Platform Refactor Plan

# First level Refactor:

| Task                               | Duration |  Resource  | Priority |
| :--------------------------------- | :------: | :--------: | :------- |
| Libraries Upgradation from 4+ to 8 | `2 days` |  `Madhan`  | `1`      |
| Single responsibility              | `3 days` |  `Kavya`   | `3`      |
| Changing the App structure         | `5 days` |  `Madhan`  | `2`      |
| Branch Cleanup                     | `.5 day` | `Ravindra` | `4`      |

# Second Level Refactor:

| Task                           | Duration  | Resource | Priority |
| :----------------------------- | :-------: | :------: | :------- |
| Enabling AOT compilation       | `2 days`  | `Kavya`  | `1`      |
| Enabling Text compression      | `0.5 day` | `Shiva`  | `3`      |
| Light house Audit Improvements |   `--`    | `Madhan` | `2`      |

# Code Level Refactor:(Low)

| Task                                               | Duration | Resource | Priority |
| :------------------------------------------------- | :------: | :------: | :------- |
| Removing Lodash (util library)                     |   `NA`   |   `--`   | `Low`    |
| Revamping the existing thought process of a module |   `NA`   |   `--`   | `High`   |

# Standards setup:

### Commit Message Convention:

We follow the [conventional commits specification](https://www.conventionalcommits.org/en) for our commit messages:

- `fix`: bug fixes, e.g. fix Button color on DarkTheme.
- `feat`: new features, e.g. add Snackbar component.
- `refactor`: code refactor, e.g. new folder structure for components.
- `docs`: changes into documentation, e.g. add usage example for Button.
- `test`: adding or updating tests, eg unit, snapshot testing.
- `chore`: tooling changes, e.g. change circleci config.
- `BREAKING CHANGE`: for changes that break existing usage, e.g. change API of a component.

Our pre-commit hooks verify that your commit message matches this format when committing.
