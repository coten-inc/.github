# .github

Default community health files for the `coten-inc` organization.

GitHub applies the files here to every repository in the organization that does
not ship its own copy. A repository-local file always wins, so a repository that
needs something different can keep its own version.

| File | Applies to |
|------|------------|
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | The pre-filled body of every new pull request |

The pull request template follows
[Google's engineering practices for change descriptions](https://google.github.io/eng-practices/review/developer/cl-descriptions.html):
the title is a standalone imperative line, and the body explains why the change
is needed rather than restating the diff.

This repository is public because GitHub only distributes default community
health files from a public `.github` repository. Keep organization-internal
details out of it — the files here are visible to anyone.
