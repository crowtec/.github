<!--
Title: a Conventional Commit, e.g. `feat(cart): add discount codes`.
It becomes the squash commit and decides the release (feat = minor, fix = patch).
-->

## What and why

<!-- The change in one or two sentences, and the reason for it. -->

Trello card: <!-- link -->

## How it was verified

- [ ] `mise run gate`, or the part that applies: <!-- which -->
- [ ] Checked by hand: <!-- what, where (local, preview, staging) -->

## Risk

- [ ] Touches money, auth, personal data, a migration or infrastructure (needs integration tests and a careful review)
- [ ] Breaking change (a `BREAKING CHANGE:` footer is added at the end of this description)

Rollback: <!-- revert the PR / redeploy the previous release / something more, and what -->

## Screenshots

<!-- For anything visible: before and after. Delete this section otherwise. -->
