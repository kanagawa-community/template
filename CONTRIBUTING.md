<!--
Fill in the placeholders and keep this file short. The organization guide
already covers commits, checks, and pull requests, so link to it instead of
repeating it. Replace every {{PLACEHOLDER}} and delete this comment.
-->

# Contributing to Kanagawa for {{APPLICATION}}

Thanks for helping. This port follows the
[Kanagawa community contributing guide](https://github.com/kanagawa-community/.github/blob/main/.github/CONTRIBUTING.md),
which explains conventional commits, the checks every pull request runs, and how
changes are reviewed. This page covers only what is specific to this port.

## Where to report what

- Problems with the theme in {{APPLICATION}}, such as wrong colors, poor
  contrast, or a missing variant, belong in this repository's
  [issue tracker](https://github.com/kanagawa-community/{{REPOSITORY}}/issues).
- Problems in {{APPLICATION}} itself belong with its maintainers, not here. Start
  from the [application's page]({{APPLICATION_URL}}).
- Changes to the colors themselves belong in the
  [shared palette](https://github.com/kanagawa-community/.github/blob/main/PALETTE.md),
  not in this port. Open an issue in the
  [.github repository](https://github.com/kanagawa-community/.github/issues)
  so every port stays in step.

## Colors

Take colors from the shared [palette](https://github.com/kanagawa-community/.github/blob/main/PALETTE.md)
and follow the [style guide](https://github.com/kanagawa-community/.github/blob/main/STYLE-GUIDE.md).
Do not sample colors from screenshots or add new ones. Every change must work in
Wave, Dragon, and Lotus.

## Working on this port

{{DEVELOPMENT_INSTRUCTIONS}}

<!--
Say how to try a change locally, which files are generated and how to regenerate
them, and how to preview each variant.
-->

## Pull requests

- Keep each pull request to one change, and include a screenshot of each variant
  it affects.
- Update the README when installation or usage changes.
