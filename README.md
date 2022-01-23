# Connected Web Ownership Tools

Ownership tools for managing and maintaining the public repositories attached to the connected-web organisation.

## Repositories

- `repolist.txt` contains a list of repositories to monitor and update

## Auditing Repos

Raises PRs across multiple repos: 

- `jumper -l repolist.txt -s audit -r ownership`

## Installing Latest Dependencies

Raises PRs across multiple repos: 

- `jumper -l repolist.txt -s rebuild -r ownership`

## Check repos for a PR Checker (Github Workflow) and create if not found

Raises PRs across multiple repos: 

- `jumper -l repolist.txt -s pr-checker -r ownership`

## Check repos that use linters; upgrade the linter, and fix any new linting issues

Raises PRs across multiple repos: 

- `jumper -l repolist.txt -s linting -r ownership`

## Wishlist

- Automatically generate `repolist.txt` by looking at a github organisation or user.
- Make a user interface to run these commands

## Project Support

See the [Workflow Optmisation](https://connected-web.atlassian.net/browse/WORKOP) board for related tickets.
