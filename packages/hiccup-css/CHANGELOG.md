# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.1.39](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@1.1.38...@thi.ng/hiccup-css@1.1.39) (2020-09-22)

**Note:** Version bump only for package @thi.ng/hiccup-css





## [1.1.38](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@1.1.37...@thi.ng/hiccup-css@1.1.38) (2020-09-13)

**Note:** Version bump only for package @thi.ng/hiccup-css





## [1.1.37](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@1.1.36...@thi.ng/hiccup-css@1.1.37) (2020-08-28)

**Note:** Version bump only for package @thi.ng/hiccup-css





## [1.1.36](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@1.1.35...@thi.ng/hiccup-css@1.1.36) (2020-08-17)

**Note:** Version bump only for package @thi.ng/hiccup-css





## [1.1.35](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@1.1.34...@thi.ng/hiccup-css@1.1.35) (2020-08-16)

**Note:** Version bump only for package @thi.ng/hiccup-css





# [1.1.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@1.0.19...@thi.ng/hiccup-css@1.1.0) (2019-07-07)

### Features

* **hiccup-css:** enable TS strict compiler flags (refactor) ([1e81385](https://github.com/thi-ng/umbrella/commit/1e81385))

# [1.0.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@0.3.5...@thi.ng/hiccup-css@1.0.0) (2019-01-21)

### Build System

* update package build scripts & outputs, imports in ~50 packages ([b54b703](https://github.com/thi-ng/umbrella/commit/b54b703))

### BREAKING CHANGES

* enabled multi-outputs (ES6 modules, CJS, UMD)

- build scripts now first build ES6 modules in package root, then call
  `scripts/bundle-module` to build minified CJS & UMD bundles in `/lib`
- all imports MUST be updated to only refer to package level
  (not individual files anymore). tree shaking in user land will get rid of
  all unused imported symbols.

# [0.3.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@0.2.32...@thi.ng/hiccup-css@0.3.0) (2018-12-15)

### Features

* **hiccup-css:** add animation(), add test & update readme ([aac8b6f](https://github.com/thi-ng/umbrella/commit/aac8b6f))

<a name="0.2.0"></a>
# [0.2.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@0.1.24...@thi.ng/hiccup-css@0.2.0) (2018-06-08)

### Features

* **hiccup-css:** add class scoping support ([244bf21](https://github.com/thi-ng/umbrella/commit/244bf21))
* **hiccup-css:** add injectStyleSheet() ([8d6e6c8](https://github.com/thi-ng/umbrella/commit/8d6e6c8))

<a name="0.1.1"></a>
## [0.1.1](https://github.com/thi-ng/umbrella/compare/@thi.ng/hiccup-css@0.1.0...@thi.ng/hiccup-css@0.1.1) (2018-03-05)

### Performance Improvements

* **hiccup-css:** no empty Set() creation, change type check order in css() ([105bbf4](https://github.com/thi-ng/umbrella/commit/105bbf4))
