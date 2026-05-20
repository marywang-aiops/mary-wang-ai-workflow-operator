# GitHub Publish Checklist

Do not publish until every item is checked.

## Identity Safety

- [ ] The Mary Wang GitHub account has been created with `939172168@qq.com`.
- [ ] The email has been verified.
- [ ] 2FA has been enabled.
- [ ] `gh auth status` shows the Mary Wang username.
- [ ] `gh auth status` does not show active account `Erica1018`.

## Privacy Safety

- [ ] `.gitignore` contains `private/`.
- [ ] `private/payment/wechat.jpg` exists locally.
- [ ] `private/payment/alipay.jpg` exists locally.
- [ ] `git status --short --ignored` does not list private payment files as trackable files.
- [ ] README and service page do not display QR codes.

## Repo Setup

Repository name:

`mary-wang-ai-workflow-operator`

Description:

`AI workflow audit templates and service materials for non-technical founders.`

Visibility:

`Public`

Recommended topics:

- `ai-workflow`
- `automation`
- `non-technical-founders`
- `ai-ops`
- `codex`
- `openclaw`
- `templates`
- `workflow-audit`

## Local Git Identity

- [ ] `git config --get user.name` returns `Mary Wang`.
- [ ] `git config --get user.email` returns `939172168@qq.com`.

## Publish Commands

Run these only after identity safety is complete.

```powershell
git add .
git commit -m "Launch Mary Wang AI workflow operator assets"
gh repo create mary-wang-ai-workflow-operator --public --source . --remote origin --push
```

If GitHub CLI is not logged into the Mary Wang account, do not run these commands.
