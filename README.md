# commitlint-automated-release
Uses commitlint to standardize commit messages for automating releases

## How to Skip Message Linting

Use `git commit --no-verify -m "${MESSAGE}"` to avoid having your commit messages linted

## --no-verify

The `--no-verify` flag has an abbreviated form of `-n`.

`--no-verify` and `-n` can bypass the `git commit-msg` hook.

Only `--no-verify` can bypass the `git pre-push` hook.
