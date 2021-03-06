# CHANGELOG
All notable changes to this project will be documented in this file.  
This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html)

## [Unreleased]

<a name="0.0.3"></a>
## [0.0.3] - 2018-03-12
### Features
- Add support for GitLab :tada:

<a name="0.2.0"></a>
## [0.2.0] - 2018-03-02
### Features
- Add template for `Keep a changelog` to the `--init` option
- Supports vim like `j/k` keybind with item selection of `--init`

### Bug Fixes
- Support Windows colors :tada: ([@mattn](https://github.com/mattn))
- Fixed several bugs in Windows

<a name="0.1.0"></a>
## [0.1.0] - 2018-02-25
### Bug Fixes
- Fix error message when `Tag` can not be acquired
- Fix `Revert` of template created by Initializer

### Code Refactoring
- Refactor `Initializer` to testable

### Features
- Supports annotated git-tag and adds `Tag.Subject` field [#3](https://github.com/git-chglog/git-chglog/issues/3)
- Remove commit message preview on select format
- Add Git Basic to commit message format
- Add preview to the commit message format of `--init` option

<a name="0.0.2"></a>
## [0.0.2] - 2018-02-18
### Bug Fixes
- Fix a bug that `Commit.Revert.Header` is not converted by `GitHubProcessor`

### Features
- Add preview to the commit message format of `--init` option

<a name="0.0.1"></a>
## 0.0.1 - 2018-02-18
### Bug Fixes
- Fix parsing of revert and body

### Code Refactoring
- Fix typo
- Change to return an error if corresponding commit is empty
- Refactor the main logic

### Features
- Add cli client
- Add commits in commit version struct
- Add config normalize process
- Add Next and Previous in Tag
- Add MergeCommits and RevertCommits
- First implement

[Unreleased]: https://github.com/git-chglog/git-chglog/compare/0.0.3...HEAD
[0.0.3]: https://github.com/git-chglog/git-chglog/compare/0.2.0...0.0.3
[0.2.0]: https://github.com/git-chglog/git-chglog/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/git-chglog/git-chglog/compare/0.0.2...0.1.0
[0.0.2]: https://github.com/git-chglog/git-chglog/compare/0.0.1...0.0.2
