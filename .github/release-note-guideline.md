# Release Note Guide

> references [ESLint](http://eslint.org/blog/), [Vuejs](https://github.com/vuejs/vue/releases)

## Title
* should be a tag name.
* follows [semantic versioning](http://semver.org/).  

* If this published to **npm**, tag name should start with `v` to avoid conflict with semver. For more information see [this](https://docs.npmjs.com/getting-started/using-tags#caveats).

- - -

## Description Format
```
## Highlights
* Short Description on change
  more descriptions if necessary
* Short Description on change
* Short Description on change
- - -

<Changes>
```

### Highlights Description
* summary of this release, user should know.
* can be anything in `<Changes>`. It could be a bug fix, updating feature, add new feature, etc.
* order __Short Description__ by importance

### Changes
```
## <type-of-changes1>
* <short-hash> <pull-request-title> (<PR-id>)

## <type-of-changes2>
* <short-hash> <pull-request-title> (<PR-id>) 
* <short-hash> <pull-request-title> (<PR-id>) (@<contributer>)
```
* `<short-hash>` is a last merge commit, before PR received.
* add `<contributer>` only if contributer is not manitainer/owner.

### Type of Changes
* **Features** - Commit start with `New`, `feat`
* **Enhancements** - Commit start with `Update`, `refactor`, `perf`
* **Bug Fixes** - Commit start with `fix`
* **Documentation** - Commit start with `docs`
* **Chores** - Commit start with `style`, `test`, `chore`
