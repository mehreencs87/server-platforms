# Auth0's server platforms

[WIP] This is a repository for mapping all supported server platforms by [Auth0](https://auth0.com/)

## Release

Make sure you have [bump](https://github.com/ianstormtaylor/bump) and [git-extras](https://github.com/tj/git-extras)
Follow the next steps:

``` bash
  # Once finished your changes and commit them, run:
  bump {patch,minor,major,VERSION}

  # Then create the changelog for the release, using
  # the retrieved version by last command:
  git changelog --tag <version>

  # Then, just run:
  git add . && git release <version>

  # Done!
```
