# release-drafter-example

![](https://media.giphy.com/media/CDZwopbecAbIc/giphy-downsized.gif)

This repository demonstrates how to use [release-drafter](https://github.com/marketplace/actions/release-drafter) github action.
Also, there is another [github action](./.github/workflows/release_slack_notification.yml) added for sending notification to a slack channel at every new release creation.

## Labels

The draft change note is constructed based on the available github labels:

### Change releated labels

- bug - Something isn't working
- chore - Changes that do not relate to a bug or feature
- feature - New feature or improvement
- chore - Changes that do not relate to a bug or feature

### Semantic versioning labels

### Other

- skip-changelog - Won't be included in the changelog

You can find them [here](https://github.com/joelazar/releaser-example/issues/labels) too.
