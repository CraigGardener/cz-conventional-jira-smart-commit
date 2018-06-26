# cz-conventional-jira-smart-commit

[![Greenkeeper badge](https://badges.greenkeeper.io/CraigGardener/cz-conventional-jira-smart-commit.svg)](https://greenkeeper.io/)

A commitizen adapter for
[JIRA smart commits](https://confluence.atlassian.com/display/FISHEYE/Using+smart+commits).

## Usage

### Add this adapter

Install this adapter

```
npm install cz-conventional-jira-smart-commit
```

Reference it in your `.cz.json` of your project

```json
{
  "path": "node_modules/cz-conventional-jira-smart-commit/"
}
```

or use commitizen to init
```
commitizen init cz-conventional-jira-smart-commit
```


### Day to day work

Instead of `git commit -m 'Your message'`, you type: `git cz` with this adapter and it prompts you for:

- Commit Type
- Commit Scope
- Short Message
- Long Description
- JIRA Issue(s)
- JIRA Workflow Command
- JIRA Time Spent
- JIRA Issue Comment

And generates your commit based on that.
