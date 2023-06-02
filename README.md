# Community-maintained SLSA buildTypes for GitHub Actions

This repo contains community-maintained
[SLSA Provenance](https://slsa.dev/provenance/v1) `buildType` definitions for
GitHub Actions.

These definitions are hosted and maintained by the SLSA community, not GitHub.
Our hope is for GitHub Actions to eventually host and maintain this definition,
served under a URL it controls, once it officially supports SLSA. In the
meantime, this unofficial definition can be used by tooling such as
[slsa-github-generator] to describe a GitHub Actions builds.

[slsa-github-generator]: https://github.com/slsa-framework/slsa-github-generator

## What's in this repo

-   [docs/](docs/): GitHub Pages configuration for
    https://slsa-framework.github.io/github-actions-buildtypes/. This is a very
    simple set of redirects to the corresponding pages in the GitHub UI. This is
    an easy way to maintain a stable `buildType` URI without having to worry
    about a static site generator, themes, and so on.

-   [workflow/v1](workflow/v1): `buildType` for a top-level GitHub Actions
    Workflow.
