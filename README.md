## workflows
### Purpose
This repository will store reusable workflows for GitHub Actions for use by other Sanctum projects.
~~Since we're still in the early stages of development, we're not opening this up to the public yet.~~

I am happy to announce the first release of this repository!
All workflows will be made available under the Apache 2.0 license.

### Examples
#### [`gradle.yml`](./.github/workflows/gradle.yml)
This workflow is used to build Sanctum projects that use Gradle.

[`setup-gradle`](https://github.com/gradle/actions?tab=readme-ov-file#the-setup-gradle-action) is used to speed up builds by caching
Gradle's runtime environment, once prepared. Gradle's distribution and cache are saved to repository cache.

By default, this workflow also caches the outputs of the build. This can be augmented with configuration. 
##### Copyright 2023-2025 Sanctum Team
