# Changelog

## Unreleased

## 0.9.1 - 2022-09-22

### Fixed

- Fix an unexpected symbol for preparation command.
- Remove unnecessary `env` and revert to `bundle install`.

## 0.9.0 - 2022-09-22

### Changed

- Change `bundle install` to `env bundle install`.

## 0.8.0 - 2022-09-21

### Added

- Add `preparation_command` option.

### Changed

- Always `--regenerate-todo` and remove the `rubocop_options` option.

## 0.7.0 - 2022-07-19

### Changed

- Support Gemfile\* patterns and remove `another_gemfile` option.

## 0.6.2 - 2022-06-04

### Fixed

- Fixed a RuboCop updates would include changes to other gems when using different Ruby versions.

## 0.6.1 - 2022-06-03

### Changed

- Use `bundle config set --local without`.

## 0.6.0 - 2022-06-03

### Added

- Add mode inputs.

## 0.5.2 - 2022-06-03

### Changed

- Unification of detailed expressions was implemented.

## 0.5.1 - 2022-06-03

### Changed

- Add without setting for bundle install steps.

## 0.5.0 - 2022-06-01

### Changed

- Change to get Ruby version from `.ruby-version`.

## 0.4.0 - 2022-05-31

### Changed

- Update PR title and body.
- Add step for update target RuboCop (extension) to be updated for another Gemfile.

## 0.3.0 - 2022-05-31

### Changed

- Update to add inputs to change behavior.
- Update actions are outlined and the name of each step was clarified.

## 0.2.0 - 2022-05-30

### Added

- Add update steps.

## 0.1.0 - 2022-05-19

### Added

- Initial release.
