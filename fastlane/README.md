fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios import_and_cache_ci_utilities

```sh
[bundle exec] fastlane ios import_and_cache_ci_utilities
```



### ios download_development_certificates

```sh
[bundle exec] fastlane ios download_development_certificates
```



### ios lint

```sh
[bundle exec] fastlane ios lint
```

Runs quick pod lib lint

### ios lint_full

```sh
[bundle exec] fastlane ios lint_full
```

Runs full pod lib lint

### ios release_current

```sh
[bundle exec] fastlane ios release_current
```



### ios pod_code_coverage

```sh
[bundle exec] fastlane ios pod_code_coverage
```

Check code coverage on project

### ios check_string_macros

```sh
[bundle exec] fastlane ios check_string_macros
```

Verify string macro usages

### ios generate_service_integrations

```sh
[bundle exec] fastlane ios generate_service_integrations
```

Generates service integrations

### ios test

```sh
[bundle exec] fastlane ios test
```

Runs all the unit tests

### ios test_scheme_app

```sh
[bundle exec] fastlane ios test_scheme_app
```

Runs all Scheme App unit tests

### ios uitest

```sh
[bundle exec] fastlane ios uitest
```

Run all UITests

### ios string_gen

```sh
[bundle exec] fastlane ios string_gen
```

Generates strings and updates strings unit tests

### ios tokenize_strings

```sh
[bundle exec] fastlane ios tokenize_strings
```

Tokenize strings

### ios release_current_ci_utilities

```sh
[bundle exec] fastlane ios release_current_ci_utilities
```

Pushes the current podspec to the memberspecs repo

### ios mem_pod_quick_lint_podspec

```sh
[bundle exec] fastlane ios mem_pod_quick_lint_podspec
```



### ios mem_pod_code_coverage

```sh
[bundle exec] fastlane ios mem_pod_code_coverage
```

Check code coverage on project

### ios mem_pod_full_lint_podspec

```sh
[bundle exec] fastlane ios mem_pod_full_lint_podspec
```

Runs pod lib lint on DSYLogger

### ios mem_pod_release_current

```sh
[bundle exec] fastlane ios mem_pod_release_current
```



### ios download_development_certificates_profiles

```sh
[bundle exec] fastlane ios download_development_certificates_profiles
```



### ios create_development_certs_discovery_team

```sh
[bundle exec] fastlane ios create_development_certs_discovery_team
```

Needs to be run with appropriate level access - it is likely not you

### ios create_development_certs_bankmed_team

```sh
[bundle exec] fastlane ios create_development_certs_bankmed_team
```

Needs to be run with appropriate level access - it is likely not you

### ios release_code_and_framework

```sh
[bundle exec] fastlane ios release_code_and_framework
```

Called from a pod's release workflow in bitrise, not to be called directly

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
