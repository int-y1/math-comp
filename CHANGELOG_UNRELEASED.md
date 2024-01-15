# Changelog (unreleased)

To avoid having old PRs put changes into the wrong section of the CHANGELOG,
new entries now go to the present file as discussed
[here](https://github.com/math-comp/math-comp/wiki/Agenda-of-the-April-23rd-2019-meeting-9h30-to-12h30#avoiding-issues-with-changelog).

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added

- in `finset.v`
  + lemmas `big_set1E`, `big_imset_idem`.

### Changed

- Notations declared in the `fun_scope` are now declared in the
  `function_scope`.
- in `finset.v`
  + generalized lemmas `big_set0` and `big_set` from semigroups
    to arbitrary binary operators

### Renamed

### Removed

### Deprecated

- in `ssrfun.v`
  + notation scope `fun_scope`, use `function_scope` instead

### Infrastructure

### Misc

