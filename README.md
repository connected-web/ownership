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
