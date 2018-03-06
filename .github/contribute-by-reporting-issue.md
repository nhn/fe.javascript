# Register Issue

> references [ESLint](http://eslint.org/docs/developer-guide/contributing/)

## Bug Report
Create a new issue if you found a new issue, or have a question.
Please fill out [issue template]() to help us understand your report.

## Issue Classification
> references [Robin Powered](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/),
[roslyn/wiki](https://github.com/dotnet/roslyn/wiki/Labels-used-for-issues), [dany lunny](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63),
[ESLint](http://eslint.org/docs/developer-guide/contributing/working-on-issues)

### Examination
* **triage** - not yet checked
* **accepted** - issue was checked, and we agree on your report.
* **invalid** - don't fit issue format
* **wontfix** - determined by policy, may be it could resolved by other approach, or it's need much resource than it's usages
* **duplicate** - have similar issue report

### Type
* **bug** - need fix
* **documentation** - need update document not a code. (e.g. comment, README)
* **feature** - request new feature
* **enhancement** - request updating exist feature
* **question** - can help you by correct miss understanding point

### Status
* **in progress** - started working
* **in review** - resolved issue, and ready to submit PR for review

## Communicate with label
As explained above, there are three type of label. Same type cannot assigned at the same type.
It represent progress of issue. If there is no labeling or no comment in 7 days, ping us!

### Wait Examination
When new issue is registered, the default label is __triage__.
It has only one label(triage) until we review it.

### Sort issue
- acceptable
label changed to __acceptable__.
A __well-chosen TYPE label__ will be assigned.
When resolving starts, __STATUS label__ will be added.

- not acceptable
label changed to one of __inactive label__(invalid, wontfix, duplicate).

### Close issue
Close issue, if it is __resolved__ or __inactive__.
