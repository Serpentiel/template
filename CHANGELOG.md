# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

<!-- markdownlint-disable-next-line -->
<!-- ### Added -->

<!-- markdownlint-disable-next-line -->
<!-- ### Changed -->

<!-- markdownlint-disable-next-line -->
<!-- ### Deprecated -->

<!-- markdownlint-disable-next-line -->
<!-- ### Removed -->

<!-- markdownlint-disable-next-line -->
<!-- ### Fixed -->

- Ignore dependabot's commit messages in `commitlint` check

<!-- markdownlint-disable-next-line -->
<!-- ### Security -->

## [1.3.1] - 2023-02-12

<!-- markdownlint-disable-next-line -->
### Added

- `commitlint` linter

## [1.3.0] - 2022-08-26

<!-- markdownlint-disable-next-line -->
### Added

- Skip labels for Changelog Enforcer
- Skip workflows label for Dependency Review
- Skip workflows label for Lint
- Auto Approve workflow

<!-- markdownlint-disable-next-line -->
### Changed

- Disabled creation of issues without using a template
- Disabled Changelog Enforcer for dependabot

<!-- markdownlint-disable-next-line -->
### Removed

- Dropped comment from Dependency Review workflow

<!-- markdownlint-disable-next-line -->
### Fixed

- Prevent Changelog Enforcer from triggering on `push` events

## [1.2.5] - 2022-07-30

<!-- markdownlint-disable-next-line -->
### Removed

- `markdownlint` comments from PR template

<!-- markdownlint-disable-next-line -->
### Fixed

- Changelog links

## [1.2.4] - 2022-07-29

<!-- markdownlint-disable-next-line -->
### Added

- Some info to `README.md`
- Attribution to Font Awesome project

<!-- markdownlint-disable-next-line -->
### Changed

- Drop title case from issue template names

<!-- markdownlint-disable-next-line -->
### Fixed

- GitHub username in `FUNDING.yml`
- Logo size in `README.md`

## [1.2.3] - 2022-07-29

<!-- markdownlint-disable-next-line -->
### Changed

- Update license links in `README.md`
- Use `pull_request` event in GitHub Actions workflows

<!-- markdownlint-disable-next-line -->
### Fixed

- Line length in `README.md`

## [1.2.2] - 2022-07-29

<!-- markdownlint-disable-next-line -->
### Removed

- Security policy contact link

## [1.2.1] - 2022-07-29

<!-- markdownlint-disable-next-line -->
### Changed

- Release branch wildcard in GitHub Actions workflows
- Run possible GitHub Actions workflows on push too

## [1.2.0] - 2022-07-29

<!-- markdownlint-disable-next-line -->
### Added

- `lint.yml` GitHub Actions workflow featuring `markdownlint`
- `dependabot.yml` GitHub config
- `changelog_enforcer.yml` GitHub Actions workflow
- `dependency_review.yml` GitHub Actions workflow
- `CODEOWNERS`
- `SECURITY.md`
- `ATTRIBUTION.md`

<!-- markdownlint-disable-next-line -->
### Changed

- Drop trailing dots from list items in `CONTRIBUTING.md`
- Rename lint job in `lint_markdown_files.yml`
- Rework lint GitHub Actions workflow
- Use dashes instead of underscores in workflows
- Rename `LICENSE` to `LICENSE.md`
- Return underscores to filenames under `.github`
- Enable workflows for PRs to release branches
- Exclude `LICENSE.md` from `markdownlint`
- Set GitHub Actions workflows permissions
- Update `README.md`, `CONTRIBUTING.md` and `.github/config.yml` with links to `SECURITY.md`
- Improve pull request template

<!-- markdownlint-disable-next-line -->
### Removed

- `enforce_changelog_entries.yml` GitHub Actions workflow

<!-- markdownlint-disable-next-line -->
### Fixed

- `dependency_review.yml` GitHub Actions workflow
- Styling in `CODE_OF_CONDUCT.md` and `SECURITY.md`

## [1.1.0] - 2022-07-28

<!-- markdownlint-disable-next-line -->
### Added

- `FUNDING.yml` GitHub config
- `enforce_changelog_entries.yml` GitHub Actions workflow

<!-- markdownlint-disable-next-line -->
### Changed

- Drop title case for `enforce_changelog_entries.yml` GitHub Actions workflow's name
- Update issue quicklinks in `README.md` to use templates

## [1.0.1] - 2022-07-28

<!-- markdownlint-disable-next-line -->
### Changed

- Lowercase the documentation word in `CONTRIBUTING.md`

## [1.0.0] - 2022-07-28

<!-- markdownlint-disable-next-line -->
### Added

- The template
- The changelog

<!-- VERSION DIFFLINKS -->
[Unreleased]: https://github.com/Serpentiel/template/compare/v1.3.1...main
[1.3.1]: https://github.com/Serpentiel/template/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/Serpentiel/template/compare/v1.2.5...v1.3.0
[1.2.5]: https://github.com/Serpentiel/template/compare/v1.2.4...v1.2.5
[1.2.4]: https://github.com/Serpentiel/template/compare/v1.2.3...v1.2.4
[1.2.3]: https://github.com/Serpentiel/template/compare/v1.2.2...v1.2.3
[1.2.2]: https://github.com/Serpentiel/template/compare/v1.2.1...v1.2.2
[1.2.1]: https://github.com/Serpentiel/template/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/Serpentiel/template/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/Serpentiel/template/compare/v1.0.1...v1.1.0
[1.0.1]: https://github.com/Serpentiel/template/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/Serpentiel/template/releases/tag/v1.0.0
