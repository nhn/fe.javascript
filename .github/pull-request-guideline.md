# Pull Requests

> This Guide is base on [CocoaPods](http://guides.cocoapods.org/contributing/contribute-to-cocoapods.html), [ESLint](http://eslint.org/docs/developer-guide/contributing/pull-requests)  

Development Workflow
- Set up your development environment with [develoment environment](development-environment.md)
- Pick up an [Issue](https://github.nhnent.com/youjung-hong/tui-github-guide/issues). See issue classification explained below
- Check the CONTRIBUTING requirements
- Make a pull request

## Pick up an issue
[Issue Classification](contribute-by-reporting-issue.md#issue-classification) will help you to pick up an issue.  
Create master issue, if issues are too small

## Make changes
### Checkout New branch
**Default Branches**
- master: lastest release branch
- develop: PR base branch, developing now
- gh-pages: api docs and examples

**Branch Naming Guide**

> reference [ikaruce/git-style-guide#branches](https://github.com/agis/git-style-guide#branches)

```
<tag>(/short-description)/<issue-id>
```
* `<tag>`: [commit message type](https://github.nhnent.com/youjung-hong/tui-github-guide/blob/master/.github/commit-message-convention.md#type), issue, issues
* Choose __short__ and __descriptive__ names  
* Use __hyphens__ to separate words  
* Identify GitHub __issue__ or __pull request__ number  

**Good**
```
    fix/indentation-error/122
    issues/update-documentaion/145-134-133 // 이슈 여러 개
    issues/focus-blur/124 // 마스터 이슈
    refactor/correct-typos/123
    feat/multiline-ternary-option/44
    issue/npm-publish/13
```

### Check Code Style  
Run `npm run eslint` and make sure all the tests pass. Fail even WARNING!

### Test
Run `npm run test` and verify all the tests pass.  
If you are adding new commands or features, they must include tests.  
If you are changing functionality, update the tests if you need to.

### Commit
Follow our [commit message-conventions](commit-message-convention.md).  
Run `npm run check-commit` and check commit message format.

## Yes! Pull request
Make your pull request, then describe your changes.
### Title
Follow other PR title format on below.
```
    <Type>: Short Description (close: #xxx)
    <Type>: Short Description (fix: #111)
    <Type>: Short Description (fix: #123, #111, #122)
    <Type>: Short Description (ref: #111)
```
* capitalize first letter of Type
* use present tense: 'change' not 'changed' or 'changes'

### Description
If it is related to an issue, add a link to the issue(like `#12`) in the description.
Fill in the [PULL_REQUEST_TEMPLATE](PULL_REQUEST_TEMPLATE.md) by check your case.

## After merged
Congulatulation! After merged, your branch is unnecessary. Please **delete your PR branch**.
