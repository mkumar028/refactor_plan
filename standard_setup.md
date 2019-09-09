# Standards to follow

### Editor Preference

Indentation Rule:

- HTML, set tab size as `2`.
- JS, set tab size as `4`.
- CSS, set tab size as `2`.

Always use tab over spaces.

### Coding Rule

To ensure consistency throughout the source code, keep these rules in mind as you are working:

- Before pushing the code to repository, make sure all the log statements are removed.
- We follow Airbnb's JavaScript Style Guide, but wrap all code at 100 characters.

### Commit Message Convention

We follow the [conventional commits specification](https://www.conventionalcommits.org/en) for our commit messages:

- `fix`: bug fixes, e.g. fix Button color on DarkTheme.
- `feat`: new features, e.g. add Snackbar component.
- `refactor`: code refactor, e.g. new folder structure for components.
- `docs`: changes into documentation, e.g. add usage example for Button.
- `test`: adding or updating tests, eg unit, snapshot testing.
- `BREAKING CHANGE`: for changes that break existing usage, e.g. change API of a component.

Our pre-commit hooks verify that your commit message matches this format when committing.

### Git Branch Name Convention

When you are creating a branch pls check with the below convention if it is a
- Feature: prefix your branch name with feature/{*your branch name*}.
- Bug: prefix your branch name with bug/{*your bug name/no*}.
- Refactor: prefix your branch name with refactor/{*module name of the app*}.
- Hotfix: any prod issue or thing needs to be addressed immediately, prefix your change with hotfix/{*regds your fix*}.

Stable Branch:
- There should always only one develop, and one master branch for a client (Since we might have different client for a project).
- We should create git tags for every release to production with the name as feature to the last commit.

### Sending a pull request

When you're sending a pull request:

- Prefer small pull requests focused on one change.
- Verify all tests are passing and no lint errors.
- Preview the documentation to make sure it looks good.

When you're working on a component:

- Follow the guidelines described in the [official material design docs](https://material.io/guidelines/).
- Write a brief description of every prop when defining to aid with documentation.
- Provide an example usage for the component (refer some open source libraries to get a idea).
