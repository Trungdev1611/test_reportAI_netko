# test_reportAI_netko

Repository used to validate deploy-report integration.

## Test convention

- Commit messages should follow: `issue-<iid>/content`
- Example: `issue-123/add smoke test file`

This helps the bot map GitHub commits to GitLab issue IID.

## Husky (commit-msg)

Sau `npm install`, hook `commit-msg` sẽ chặn commit nếu message không chứa `issue-<IID>/`. Merge và Revert không bị chặn.

Làm việc trong repo này (không commit từ root `hackAI` — thư mục này nằm trong `.gitignore` của monorepo cha).
