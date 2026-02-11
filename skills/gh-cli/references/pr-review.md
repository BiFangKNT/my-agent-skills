# gh pr review

```bash
gh pr review 123 --comment --body "请补充回归测试说明。"
gh pr review 123 --approve --body "LGTM"
gh pr review 123 --request-changes --body "请修复空指针分支。"
```

用途：提交 PR 审查意见（评论/批准/请求修改）。
