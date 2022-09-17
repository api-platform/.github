| Q             | A
| ------------- | ---
| Branch?       | main for features / current stable version branch for bug fixes <!-- see below -->
| Tickets       | #... <!-- please link related issues if existing -->
| License       | MIT
| Doc PR        | api-platform/docs#... <!-- required for new features -->
<!--
Replace this notice by a short README for your feature/bugfix. This will help people
understand your PR and can be used as a start for the documentation.

Branch: 
- 2.7 for bugs related to the **backward compatibility layer**, if the bug was in 2.6 let's fix it on the 3.0 branch instead
- 3.0 for bug fixes
- main for new features

Additionally:
 - Always add tests and ensure they pass.
 - Never break backward compatibility (see https://symfony.com/bc).
 - Bug fixes must be submitted against the current stable version branch.
 - Features and deprecations must be submitted against main branch.
 - Legacy code removals go to the main branch.
 - Update CHANGELOG.md file.
 - Follow the [Conventional Commits specification](https://www.conventionalcommits.org/).
-->
