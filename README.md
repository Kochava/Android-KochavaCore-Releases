## Android KochavaCore
The Kochava Android SDK is a lightweight plugin which can be easily integrated into your Android project.

[![Download](https://img.shields.io/github/v/release/Kochava/Android-KochavaCore-Releases?include_prereleases&sort=semver)](https://github.com/Kochava/Android-KochavaCore-Releases/releases)
[![Download](https://img.shields.io/maven-central/v/com.kochava.core/core)](https://search.maven.org/artifact/com.kochava.core/core)

### Installation
This plugin is not typically installed on its own and is instead included as part of one of Kochava's SDKs.
View the specific [SDK integration](https://support.kochava.com/sdk-integration/) documentation for instructions on installation.

### Support
support@kochava.com

### License
KochavaCore is available under the [Kochava Terms of Service](https://www.kochava.com/terms-of-service/).

## Default Branch

As of October 1, 2020, github.com uses the branch name ‘main’ when creating the initial default branch for all new repositories.  In order to minimize any customizations in our github usage and to support consistent naming conventions, we have made the decision to rename the ‘master’ branch to be called ‘main’ in all Kochava’s github repos.

For local copies of the repo, the following steps will update to the new default branch:

```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```
