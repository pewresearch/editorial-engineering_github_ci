# Changelog for vip-go-ci

All notable changes to this project will be documented in this file.

## [1.3.13](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.13) - 2024-05-23
- [389](https://github.com/Automattic/vip-go-ci/pull/389): Upgrade to PHPCS 3.10.1

## [1.3.12](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.12) - 2024-05-22
- [#386](https://github.com/Automattic/vip-go-ci/pull/386): Update VIPCS + dependencies
- [#388](https://github.com/Automattic/vip-go-ci/pull/388): Update PHPCS, PHPUtils and PHPCompatibility dependencies

## [1.3.11](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.11) - 2023-11-02
- [#383](https://github.com/Automattic/vip-go-ci/pull/383): Temporarily roll back git requirement

## [1.3.10](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.10) - 2023-11-02

### Updated
- [#380](https://github.com/Automattic/vip-go-ci/pull/380): Update --output functionality 
- [#381](https://github.com/Automattic/vip-go-ci/pull/381): Update minimum requirements and TODO template

## [1.3.9](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.9) - 2023-09-27

### Updated
- [#376](https://github.com/Automattic/vip-go-ci/pull/376): Attempt to fix a problem with E2E tests
- [#378](https://github.com/Automattic/vip-go-ci/pull/378): tools-init.sh: Only update in 5% of cases and a small fix
- [#379](https://github.com/Automattic/vip-go-ci/pull/379): Offically support PHP 8.2

## [1.3.8](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.8) - 2023-09-25

### Updated
- [#375](https://github.com/Automattic/vip-go-ci/pull/375): Upgrading PHPCS standards: WordPress-Coding-Standards, VIP-Coding-Standards, PHPCompatibility, PHPCSUtils and adding PHPCSExtra
- [#371](https://github.com/Automattic/vip-go-ci/pull/371): tools-init.sh: Updating lock file mechanism to be safer
- [#372](https://github.com/Automattic/vip-go-ci/pull/372): Add initial E2E test for latest-release.php
- [#373](https://github.com/Automattic/vip-go-ci/pull/373): Use GitHub API version header in latest-release.php

## [1.3.7](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.7) - 2023-09-11

### Updated
- [#367](https://github.com/Automattic/vip-go-ci/pull/367): Update phpcs-variable-analysis to v2.11.17
- [#369](https://github.com/Automattic/vip-go-ci/pull/369): PHP 8.2 compatibility for tests/integration/GitHubPrGenericSupportCommentTest.php
- [#370](https://github.com/Automattic/vip-go-ci/pull/370): Update tests/manual/create-all-pull-requests.sh
  
## [1.3.6](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.6) - 2023-09-11

### Updated
- [#365](https://github.com/Automattic/vip-go-ci/pull/365): Update tools-init.sh: New version of VIP-Coding-Standards

## [1.3.5](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.5) - 2023-06-12

### Fixes
- [#358](https://github.com/Automattic/vip-go-ci/pull/358): Fix WPScan issue: Invalid UpdateURI plugin/theme headers lead to error
- [#360](https://github.com/Automattic/vip-go-ci/pull/360): Update tools: PHPCS and phpcs-variable-analysis
- [#364](https://github.com/Automattic/vip-go-ci/pull/364): Rename class "ResultsOutputDump" in test to match file name

### Updated
- [#361](https://github.com/Automattic/vip-go-ci/pull/361): Update --output option to output more types of data
- [#362](https://github.com/Automattic/vip-go-ci/pull/362): Document type-of-change label usage and add to pull request template
- [#363](https://github.com/Automattic/vip-go-ci/pull/363): Set shivammathur/setup-php to fixed version

## [1.3.4](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.4) - 2023-02-22

### Added
- [#336](https://github.com/Automattic/vip-go-ci/pull/336): Add GitHub API version HTTP header
- [#342](https://github.com/Automattic/vip-go-ci/pull/342): Add files needed for manual testing
- [#343](https://github.com/Automattic/vip-go-ci/pull/343): Add --wpscan-api-skip-folders-in-repo-options-file parameter

### Updated
- [#332](https://github.com/Automattic/vip-go-ci/pull/332): Improve WPScan logging
- [#334](https://github.com/Automattic/vip-go-ci/pull/334): Update WPScan API results wording
- [#335](https://github.com/Automattic/vip-go-ci/pull/335): Update "local" slug determination mechanism
- [#344](https://github.com/Automattic/vip-go-ci/pull/344): Update comment in wp-core-misc.php
- [#345](https://github.com/Automattic/vip-go-ci/pull/345): Update vipgoci-run.sh.dist file: Add option to skip scanning of directories via file, alter order of commands
- [#346](https://github.com/Automattic/vip-go-ci/pull/346): Update unit and integration tests to comply with a common standard, PHP 8.2 fixes, template update
- [#347](https://github.com/Automattic/vip-go-ci/pull/347): Add PHP 8.2 to CI tests, rename one CI task
- [#350](https://github.com/Automattic/vip-go-ci/pull/350): Update integration test ResultsFilterCommentsToMaxTest.php: Mock key function
- [#349](https://github.com/Automattic/vip-go-ci/pull/349): Upgrade integration tests to a common standard
- [#348](https://github.com/Automattic/vip-go-ci/pull/348): Adding user for CI tests
- [#351](https://github.com/Automattic/vip-go-ci/pull/351): Update WPScan generic comment messaging
- [#352](https://github.com/Automattic/vip-go-ci/pull/352): Move and rename unittests ini and unittests-secrets.ini files
- [#353](https://github.com/Automattic/vip-go-ci/pull/353): Update tests/integration/WpscanScanSaveForSubmissionTest.php: Do not run tests when skip GitHub write is true
- [#356](https://github.com/Automattic/vip-go-ci/pull/356): Update tests/integration/GitHubPrReviewEventsGetTest.php: Use GitHub token if available

### Fixed
- [#337](https://github.com/Automattic/vip-go-ci/pull/337): Version number sanitizing: Allow "-" in version numbers
- [#338](https://github.com/Automattic/vip-go-ci/pull/338): WPScan fixes: Changes to file path and addon location, avoid removing items from results, add slugs to tests
- [#339](https://github.com/Automattic/vip-go-ci/pull/339): WPScan fixes: Ensure that WPScan type of items are not removed from results when filtering
- [#340](https://github.com/Automattic/vip-go-ci/pull/340): Fix output suppression in tests
- [#341](https://github.com/Automattic/vip-go-ci/pull/341): Restructure readme file, document manual testing, various updates
- [#354](https://github.com/Automattic/vip-go-ci/pull/354): Change capitalization in WPScan results
- [#355](https://github.com/Automattic/vip-go-ci/pull/355): Update tests/integration/GitHubApiLabelsTest.php: Cast PR number to integer
- [#357](https://github.com/Automattic/vip-go-ci/pull/357): Update tests/integration/GitHubAuthenticatedUserGetTest.php: Unset $this->options

## [1.3.3](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.3) - 2022-11-21

### Added
- [#320](https://github.com/Automattic/vip-go-ci/pull/320): Introduce custom file extensions with scanners

### Updated
- [#310](https://github.com/Automattic/vip-go-ci/pull/310): New exit status for HTTP API errors, update log message
- [#311](https://github.com/Automattic/vip-go-ci/pull/311): Use constants for content-type headers
- [#313](https://github.com/Automattic/vip-go-ci/pull/313): Apply constant for WordPress.org API
- [#315](https://github.com/Automattic/vip-go-ci/pull/315): Replace GitHub rate limit function with HTTP API rate limit functionality
- [#316](https://github.com/Automattic/vip-go-ci/pull/316): Update two constants related to HTTP API
- [#317](https://github.com/Automattic/vip-go-ci/pull/317): Update phpcs-variable-analysis to version 2.11.9
- [#318](https://github.com/Automattic/vip-go-ci/pull/318): Update HTTP API request functions
- [#319](https://github.com/Automattic/vip-go-ci/pull/319): IRC API update: Replace cURL functionality with vipgoci_http_api_post_url()
- [#321](https://github.com/Automattic/vip-go-ci/pull/321): Update Pixel API implementation
- [#322](https://github.com/Automattic/vip-go-ci/pull/322): Increment counter when request limit is reached
- [#323](https://github.com/Automattic/vip-go-ci/pull/323): Update GitHub Actions dependencies
- [#324](https://github.com/Automattic/vip-go-ci/pull/324): Update PHPCompatibilityWP and PHPCompatibilityParagonie dependencies
- [#325](https://github.com/Automattic/vip-go-ci/pull/325): Do not display "No issues were found...." when maximum number of comments is reached
- [#328](https://github.com/Automattic/vip-go-ci/pull/328): Update shivammathur/setup-php dependency to use @v2
- [#330](https://github.com/Automattic/vip-go-ci/pull/330): Updating references to build management software

### Fixes
- [#314](https://github.com/Automattic/vip-go-ci/pull/314): WPScan API: Add function to determine "local" slug
- [#326](https://github.com/Automattic/vip-go-ci/pull/326): Rename test class, update function name in comments
- [#327](https://github.com/Automattic/vip-go-ci/pull/327): WPScan API: Ensure comments are only submitted for changed add-ons
- [#331](https://github.com/Automattic/vip-go-ci/pull/331): Update tests/integration/WpscanScanDirsAlteredTest.php due to new fields from API

## [1.3.2](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.2) - 2022-10-18

### Added
- [#309](https://github.com/Automattic/vip-go-ci/pull/309): WPScan API integration: Add URL to commit in IRC log

### Fixed
- [#304](https://github.com/Automattic/vip-go-ci/pull/304): WPScan API: Update x-ratelimit-remaining header functionality
- [#308](https://github.com/Automattic/vip-go-ci/pull/308): Add checks to WPScan API reporting logic, ensure CVSS outputted includes precision

### Updated
- [#303](https://github.com/Automattic/vip-go-ci/pull/303): Remove OAuth 1.0a functions
- [#307](https://github.com/Automattic/vip-go-ci/pull/307): Update PULL_REQUEST_TEMPLATE

## [1.3.1](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.1) - 2022-10-05

### Fixed
- [#299](https://github.com/Automattic/vip-go-ci/pull/299): Fix: Do not report latest plugin/theme as obsolete
- [#302](https://github.com/Automattic/vip-go-ci/pull/302): Fix WPScan test

### Updated
- [#301](https://github.com/Automattic/vip-go-ci/pull/301): Update statistics logic

## [1.3.0](https://github.com/Automattic/vip-go-ci/releases/tag/1.3.0) - 2022-09-28

### Added
- [#273](https://github.com/Automattic/vip-go-ci/pull/273): Add support for WPScan API scanning

### Updated
- [#281](https://github.com/Automattic/vip-go-ci/pull/281): Small updates: Use new functions introduced in #273; update HTTP wait function; update URL in README.md; update tests
- [#295](https://github.com/Automattic/vip-go-ci/pull/295): Use local git repository when running integration tests using GitHub Actions
- [#296](https://github.com/Automattic/vip-go-ci/pull/296): Use vipgoci_cached_indication_str() function

### Fixed
- [#291](https://github.com/Automattic/vip-go-ci/pull/291): Fix two problems with local git diffs
- [#292](https://github.com/Automattic/vip-go-ci/pull/292): Rename test class to match file name
- [#293](https://github.com/Automattic/vip-go-ci/pull/293): Fix re-posted comments that contain "/**" 
- [#297](https://github.com/Automattic/vip-go-ci/pull/297): Fix bug when filtering results array
- [#298](https://github.com/Automattic/vip-go-ci/pull/298): Call htmlentities() with PHP 8.1 defaults

## [1.2.6](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.6) - 2022-08-08

### Added
 - [#289](https://github.com/Automattic/vip-go-ci/pull/289): Add allow list for file filtering function

## [1.2.5](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.5) - 2022-07-19

### Fixed
- [#287](https://github.com/Automattic/vip-go-ci/pull/287): Fix problem with removed files in non-functional auto-approvals and add sanity checks elsewhere

## [1.2.4](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.4) - 2022-07-19

### Added
- [#285](https://github.com/Automattic/vip-go-ci/pull/285): Add support for ignoring PHPCS standards during startup

### Updated
- [#274](https://github.com/Automattic/vip-go-ci/pull/274): Update files to reflect that "main" branch is now named "trunk"
- [#272](https://github.com/Automattic/vip-go-ci/pull/272): Apply WP CS and variable types to final files
- [#276](https://github.com/Automattic/vip-go-ci/pull/276): Update phpcs-variable-analysis to version 2.11.3
- [#278](https://github.com/Automattic/vip-go-ci/pull/278): Switch to GitHub Actions
- [#279](https://github.com/Automattic/vip-go-ci/pull/279): Utilize 'latest' branch in documentation and in scripts
- [#280](https://github.com/Automattic/vip-go-ci/pull/280): Re-enable auto-approval of removed SVG files
- [#283](https://github.com/Automattic/vip-go-ci/pull/283): Update PHPCS, update PHPCompatibility and add PHPCSUtils, restructure tools-init.sh

### Removed
- [#282](https://github.com/Automattic/vip-go-ci/pull/282): Remove Hashes API support
- [#284](https://github.com/Automattic/vip-go-ci/pull/284): Remove support level label feature

## [1.2.3](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.3) - 2022-04-04

### Added
- [#268](https://github.com/Automattic/vip-go-ci/pull/268): Filter IRC log messages, removing strings to ignore
- [#269](https://github.com/Automattic/vip-go-ci/pull/269): Verify commit and access to repository on start up
- 
### Updated
- [#260](https://github.com/Automattic/vip-go-ci/pull/260): Move generic HTTP functions from github-api.php and to http-functions.php
- [#261](https://github.com/Automattic/vip-go-ci/pull/261): Apply WP CS to tests and other updates: GitHubPrGenericSupportCommentTest.php, PhpcsScanValidateSniffsInOptionAndReportTest.php, Skeleton.php
- [#263](https://github.com/Automattic/vip-go-ci/pull/263): Improve GitHub API error handling
- [#262](https://github.com/Automattic/vip-go-ci/pull/262): Use exec() instead of shell_exec(), use result code
- [#264](https://github.com/Automattic/vip-go-ci/pull/264): Configuring debug mode in test-suite via environmental variables
- [#266](https://github.com/Automattic/vip-go-ci/pull/266): HTTP API: Better logging, add retry mechanism, better error detection
- [#267](https://github.com/Automattic/vip-go-ci/pull/267): Update two integration tests relating to git functionality
- [#270](https://github.com/Automattic/vip-go-ci/pull/270): Update PULL_REQUEST_TEMPLATE: Mention checking and updating all test types

### Fixed
- [#271](https://github.com/Automattic/vip-go-ci/pull/271): Set exit code for vipgoci_sysexit() called in vipgoci_runtime_measure_exec_with_retry() 

## [1.2.2](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.2) - 2022-03-08

### Added
- [#258](https://github.com/Automattic/vip-go-ci/pull/258): Update logging & memory management, retry certain HTTP requests, catch out of memory situations 

## [1.2.1](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.1) - 2022-03-07

### Added
- [#253](https://github.com/Automattic/vip-go-ci/pull/253): Extend vipgoci_runtime_measure_shell_exec() with retry capabilities, and rename function 
- [#255](https://github.com/Automattic/vip-go-ci/pull/255): PHP lint using multiple PHP versions
- [#256](https://github.com/Automattic/vip-go-ci/pull/256): Remove PHPCS retry logic, add more reporting

### Updated
- [#257](https://github.com/Automattic/vip-go-ci/pull/257):  Setting PHPCS memory limit

## [1.2.0](https://github.com/Automattic/vip-go-ci/releases/tag/1.2.0) - 2022-02-23

### Updated
- [#207](https://github.com/Automattic/vip-go-ci/pull/207): Break vipgoci_run() into multiple functions
- [#205](https://github.com/Automattic/vip-go-ci/pull/205): Use new GitHub Teams API
- [#236](https://github.com/Automattic/vip-go-ci/pull/236): Adding PHP 8.1 support and related changes
- [#242](https://github.com/Automattic/vip-go-ci/pull/242): Adding version number to TODO in PULL_REQUEST_TEMPLATE
- [#245](https://github.com/Automattic/vip-go-ci/pull/245): Different TODO items for test suites in PULL_REQUEST_TEMPLATE file
- [#247](https://github.com/Automattic/vip-go-ci/pull/247): Apply WP CS for a few files
- [#249](https://github.com/Automattic/vip-go-ci/pull/249): Update string function usage for PHP 8
- [#250](https://github.com/Automattic/vip-go-ci/pull/250): Record that feedback was submitted on auto-approval, rename function
- [#251](https://github.com/Automattic/vip-go-ci/pull/251): Fix PHPCS and support-level related tests

### Added
- [#246](https://github.com/Automattic/vip-go-ci/pull/246): Improve reporting to users

### Resolved issues
- [#238](https://github.com/Automattic/vip-go-ci/issues/238): Extra GitHub review posted when there are skipped files 
- [#40](https://github.com/Automattic/vip-go-ci/issues/40): Leave a comment if no issues found
- [#142](https://github.com/Automattic/vip-go-ci/issues/142): Move functions and functionality between files
- [#145](https://github.com/Automattic/vip-go-ci/issues/145): In GitHub reviews, report which options were altered
- [#144](https://github.com/Automattic/vip-go-ci/issues/144): Print folders that were not scanned
- [#232](https://github.com/Automattic/vip-go-ci/issues/232): Report additional information in reviews 
- [#192](https://github.com/Automattic/vip-go-ci/issues/192): Break vipgoci_run() into multiple functions
- [#128](https://github.com/Automattic/vip-go-ci/issues/128): Use new GitHub's Teams API endpoints 

## [1.1.3](https://github.com/Automattic/vip-go-ci/releases/tag/1.1.3) - 2022-01-31

### Added
- [#239](https://github.com/Automattic/vip-go-ci/pull/239): Define version 1.1.3

## [1.1.2](https://github.com/Automattic/vip-go-ci/releases/tag/1.1.2) - 2022-01-31

### Added
- [#231](https://github.com/Automattic/vip-go-ci/pull/231): Add CircleCI status badge
- [#234](https://github.com/Automattic/vip-go-ci/pull/234): Updating README.md, adding CONTRIBUTING.md, updating issue/PR templates
- [#237](https://github.com/Automattic/vip-go-ci/pull/237): Update vip-go-svg-sanitizer to version 0.9.8

## [1.1.1](https://github.com/Automattic/vip-go-ci/releases/tag/1.1.1) - 2022-01-11 

### Updated
- [#228](https://github.com/Automattic/vip-go-ci/pull/228): Update tools-init.sh for WordPress 5.9 compatibility

## [1.1.0](https://github.com/Automattic/vip-go-ci/releases/tag/1.1.0) - 2021-12-13

### Added
- [https://github.com/Automattic/vip-go-ci/pull/221]: PHP lint altered files only option (``lint-modified-files-only``)

## [1.0.9](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.9) - 2021-11-10

### Added
- [#209](https://github.com/Automattic/vip-go-ci/pull/209): Add PHPUnit configuration, create suites for unit and integration tests. And split existent tests into those two suites.
- [#200](https://github.com/Automattic/vip-go-ci/pull/200): Add vipgoci_sysexit() unit test

### Updated
- [#203](https://github.com/Automattic/vip-go-ci/pull/203): Updating README file
- [#214](https://github.com/Automattic/vip-go-ci/pull/214): Update VIPCS to ``2.3.3`` version

### Fixed
- [#204](https://github.com/Automattic/vip-go-ci/pull/204): Replaces constant with variable to build message about limit of lines per file reached
- [#217](https://github.com/Automattic/vip-go-ci/pull/217): Add skip large files conditions to post PHPCS checks
- [#208](https://github.com/Automattic/vip-go-ci/pull/208): Add logic to avoid duplicated comments about limit of lines exceeded in the same PR
- [#218](https://github.com/Automattic/vip-go-ci/pull/218): + Add logic to avoid duplicated comments about limit of lines exceeded in the same PR

## [1.0.8](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.8) - 2021-08-25

### Added
- [#186](https://github.com/Automattic/vip-go-ci/pull/186): Skip large files functionality (``skip-large-files`` and ``skip-large-files-limit`` options).
- [#189](https://github.com/Automattic/vip-go-ci/pull/189): Function ``vipgoci_options_get_starting_with()``.
- [#195](https://github.com/Automattic/vip-go-ci/pull/195): Add Sunset HTTP header detection
- [#196](https://github.com/Automattic/vip-go-ci/pull/196): Log shutdown message to IRC
- [#199](https://github.com/Automattic/vip-go-ci/pull/199): Special exit status when no implicated PR was found, retry fetching PRs
- [#198](https://github.com/Automattic/vip-go-ci/pull/198): Validate SVG files, added details to message, and formatting changed slightly, add logging
- [#201](https://github.com/Automattic/vip-go-ci/pull/201): Adding missing namespace to SVG unit-test
- [#202](https://github.com/Automattic/vip-go-ci/pull/202): Rename branch "master" to "main" in tools-init.sh

### Fixed
- [#no-issue-number](https://github.com/Automattic/vip-go-ci/commit/a8988c4b932f2f5fdf5873c33c28ae91608bbc44): Github unit test that was failing due to an out-to-date ``merge_commit_sha`` value.

## [1.0.7](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.7) - 2021-07-05

### Fixed
- [#187](https://github.com/Automattic/vip-go-ci/pull/187): Attempt to reduce GitHub API usage a bit

### Updated
- [#183](https://github.com/Automattic/vip-go-ci/pull/183): Refine help message and options
- [#185](https://github.com/Automattic/vip-go-ci/pull/185): Upgrade phpcs-variable-analysis to 2.11.1

## [1.0.6](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.6) - 2021-06-09

### Fixed
- [#152](https://github.com/Automattic/vip-go-ci/pull/152): Add status code 100 as valid GitHub post response 

### Updated
- [#174](https://github.com/Automattic/vip-go-ci/pull/174): Updating README: Add required parameters to example
- [#177](https://github.com/Automattic/vip-go-ci/pull/177): Renaming option --results-comments-sort to --review-comments-sort
- [#179](https://github.com/Automattic/vip-go-ci/pull/179): SVG scanning: Renaming source of issue
- [#181](https://github.com/Automattic/vip-go-ci/pull/181): Replace informational URL with a message

## [1.0.5](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.5) - 2021-05-18

### New

- [#169](https://github.com/Automattic/vip-go-ci/pull/169): Support for build status indication.
- [#170](https://github.com/Automattic/vip-go-ci/pull/170): Improved PHPCS logging.
- [#172](https://github.com/Automattic/vip-go-ci/pull/172): Retry PHPCS scan on failure
- [#173](https://github.com/Automattic/vip-go-ci/pull/173): Make messages in IRC queue unique before sending

## [1.0.4](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.4) - 2021-05-10

### Fixed

- [#163](https://github.com/Automattic/vip-go-ci/pull/163): New structure for requiring files
- [#166](https://github.com/Automattic/vip-go-ci/pull/166): Resolve issues with new `git diff` mechanism
- [#167](https://github.com/Automattic/vip-go-ci/pull/167): Add more unit-tests, switch to assertSame() usage

## [1.0.3](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.3) - 2021-05-03

### Temporary release, due to problems

## [1.0.2](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.2) - 2021-05-03

### Re-release to fix issues with latest-release.php, see b057081

## [1.0.1](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.1) - 2021-05-03

### Re-release to make version numbers consistent

## [1.0.0](https://github.com/Automattic/vip-go-ci/releases/tag/1.0.0) - 2021-05-03

### Fixed
- [#153](https://github.com/Automattic/vip-go-ci/pull/153): Use local git repository for sources of `git diff`, resolving problems caused by the GitHub API not returning results or skipping files for long patches (see #135).
- [#158](https://github.com/Automattic/vip-go-ci/pull/158): Fix a bug in `vipgoci_gitrepo_blame_for_file()` which can lead to PHPCS results not being posted. This will resolve #90.
- [#162](https://github.com/Automattic/vip-go-ci/pull/162): Update `testVersion` parameter in CircleCI configuration
- [#161](https://github.com/Automattic/vip-go-ci/pull/161): Update `testVersion` parameter in README.md
- [#148](https://github.com/Automattic/vip-go-ci/pull/148): Fix problem with PHPCS config files that use paths without leading `/`.
- [#150](https://github.com/Automattic/vip-go-ci/pull/150): Assign PHP linting problems a severity value.

### Updated
 - [#159](https://github.com/Automattic/vip-go-ci/pull/159): Update VIP-Coding-Standards to newer version, see #159.
 - [#143](https://github.com/Automattic/vip-go-ci/pull/143): Allow more options to be configured via repository-config file.
 - [#151](https://github.com/Automattic/vip-go-ci/pull/151): Make name of support-level field configurable.
