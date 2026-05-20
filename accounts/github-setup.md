# GitHub Setup For Mary Wang

Use this guide to create and publish from the Mary Wang GitHub account.

Important boundary:

- Do not use the currently logged-in GitHub account `Erica1018`.
- Mary Wang's GitHub account must use `939172168@qq.com`.
- A human must create the GitHub account, verify the email, accept the terms, and set 2FA.

## Recommended Account Details

Email:

`939172168@qq.com`

Username priority:

1. `marywang-aiops`
2. `marywang-workflows`
3. `marywangops`
4. `marywang-ai`

Display name:

`Mary Wang`

Bio:

`AI workflow operator for non-technical founders. I turn messy AI workflows, folders, and automation ideas into usable systems.`

Website:

Add this after the service page is hosted.

Location:

`Remote`

## Step 1: Create The Account

1. Open [https://github.com/signup](https://github.com/signup).
2. Enter `939172168@qq.com`.
3. Choose the first available username from the priority list above.
4. Create a strong password and save it somewhere you control.
5. Complete the human verification.
6. Open the QQ email inbox.
7. Find the GitHub verification email and verify the account.

## Step 2: Turn On 2FA

1. In GitHub, click the avatar in the top right.
2. Open `Settings`.
3. Open `Password and authentication`.
4. Choose `Enable two-factor authentication`.
5. Use an authenticator app or passkey.
6. Save recovery codes somewhere safe.

## Step 3: Switch The GitHub CLI

Only do this after the new Mary Wang GitHub account exists.

1. Open PowerShell.
2. Run:

```powershell
gh auth logout
```

3. Follow the prompts to log out of `Erica1018`.
4. Run:

```powershell
gh auth login
```

5. Choose:

- GitHub.com
- HTTPS
- Login with a web browser

6. When GitHub opens in the browser, log in with the Mary Wang account.
7. Run:

```powershell
gh auth status
```

8. Confirm the active account is the Mary Wang username, not `Erica1018`.

## Step 4: Publish The Repo

Use repository name:

`mary-wang-ai-workflow-operator`

Description:

`AI workflow audit templates and service materials for non-technical founders.`

Visibility:

`Public`

Do not publish until `release/github-publish-checklist.md` is complete.

