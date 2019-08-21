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

### Sending a pull request

When you're sending a pull request:

- Prefer small pull requests focused on one change.
- Verify all tests are passing and no lint errors.
- Preview the documentation to make sure it looks good.

When you're working on a component:

- Follow the guidelines described in the [official material design docs](https://material.io/guidelines/).
- Write a brief description of every prop when defining to aid with documentation.
- Provide an example usage for the component (refer some open source libraries to get a idea).
