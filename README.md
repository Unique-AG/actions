# actions
A repository with reusable GitHub Actions workflows for Unique AG 🪃.

## Versioning
Each action has a `version.yaml`. Bump `version` and list the `changes` in the same PR (the version check fails otherwise); on merge to main, the release workflow tags and releases it as `<name>@<version>`. Pin a release by SHA:

```yaml
uses: unique-ag/actions/github/app-token-create@<sha> # app-token-create@1.0.0
```
