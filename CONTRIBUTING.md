# Contribution Guidelines

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

## Core Maintainers

@matthewhudson

When contributing to this repository, please first discuss the change you wish to make via issue with the owners of this
repository before making a change.

### Contributing Code

#### Setting up Commitzen

All @ajetreo projects use Commitizen (with the `cz-conventional-changelog` adapter) to maintain consistent commit messages.
When you commit with Commitizen, you'll be prompted to fill out any required commit fields at commit time.

```sh
npm install -g commitizen cz-conventional-changelog
```

This allows you to run `git cz`.

#### Submitting your Changes

1. Clone or fork the repo
2. Create a branch against `master` (`git checkout -b feature`)
3. Make change(s)
4. Commit your changes (`git add && git cz`)
5. Push to the branch (`git push origin feature`)
6. Open a Pull Request

### Pull Request Process

1. Create a Pull Request against the `master` branch with your changes.
2. If you are pleased with all your changes, you can now request a review from one of the owners.

Be careful, a PR can be merged only if **ALL** the required CI jobs are green. Which means the project is:

- building properly
- respecting the lint rules
- passes all the unit tests, and covers 100% of the code base
