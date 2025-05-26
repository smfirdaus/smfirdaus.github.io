# M Firdaus' personal website

[![Jekyll](https://img.shields.io/gem/v/jekyll?label=jekyll)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll?label=minimal%20mistakes)](https://rubygems.org/gems/minimal-mistakes-jekyll)

This is the repository for my personal website. Visit it at [smfirdaus.github.io](https://smfirdaus.github.io)

## Credits

The website is inspired by [Jonas Renault](https://jrenault.fr), and based on Michael Rose's [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme.


## Google Analytics

Google Analytics is enabled using Minimal Mistakes' [support](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#analytics). To avoid sharing the tracking id on github, the `__GA_TRACKING_ID__` variable in [_config.yml](./_config.yml) is replaced during deployment to Github Pages in the [workflow](./.github/workflows/jekyll.yml). To function properly, you must create a `build` environment in your repository, and [add a secret variable](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#creating-secrets-for-an-environment) named `GA_TRACKING_ID` with the Google Analytics tracking id value.
