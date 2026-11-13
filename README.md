# Contributor License Agreement

This repository contains the [Contributor License Agreement](CLA.md) (CLA) for all projects of [@avently](https://github.com/avently) and the signatures of contributors who have accepted it.

## For contributors

When you open your first pull request in any of the projects, a bot asks you to sign the CLA. To sign it, post the following comment in the pull request:

```
I have read the CLA Document and I hereby sign the CLA
```

You sign once: the signature applies to all projects and all your Contributions, as described in the CLA. Every author of the commits in a pull request must sign, so make sure that the e-mail of your commits is linked to your GitHub account.

## Versions

Each version of the CLA is published under a git tag and is never changed afterwards. Signatures for each version are stored separately.

| Version | Document | Signatures |
| --- | --- | --- |
| 1.0 | [CLA.md@v1.0](https://github.com/avently/cla/blob/v1.0/CLA.md) | `signatures/v1/cla.json` |

The signatures file is created by the bot on the first signature and must not be created or edited manually.

## Releasing a new CLA version

1. Update `CLA.md`, increase the version in its header and tag the commit, e.g. `v2.0`.
2. In every project workflow, update `path-to-document` to the new tag and `path-to-signatures` to a new file, e.g. `signatures/v2/cla.json`, so that contributors are asked to accept the new version.
3. Add the new version to the table above.
