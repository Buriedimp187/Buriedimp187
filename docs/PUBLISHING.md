# View, test and publish

The profile is a **special repository**: a public repository whose name is exactly your username (`Buriedimp187`) shows its `README.md` at the top of your profile page.

## 1. View locally
Open `assets/banner/banner.svg` and the logos in a browser. Check the banner at full width and at ~350 px, and the logo at 32×32.

## 2. Test on GitHub (optional)
A **private** repo named `Buriedimp187` does not show on the profile, so test under another name, e.g. `profile-test` (private). Push the files there and open `README.md` in both themes (Settings → Appearance). Delete the test repository afterwards.

## 3. Set your commit identity (once)
Commits are public. Avoid exposing a personal address by using your GitHub no-reply email (GitHub → Settings → Emails → "Keep my email addresses private", then copy the `ID+username@users.noreply.github.com` address):

```powershell
git config --global user.name "Your Name"
git config --global user.email "ID+Buriedimp187@users.noreply.github.com"
```

## 4. Create the repository on GitHub
1. GitHub → **New repository**.
2. Name: exactly `Buriedimp187`. Visibility: **Public**.
3. Leave **Add a README**, `.gitignore` and license **unchecked** (the folder already has these files).
4. Click **Create repository**.

## 5. Commit and push (from this folder)
```powershell
cd C:\Users\jpram\Downloads\GitHub\Buriedimp187
git init -b main
git add .
git status
git commit -m "Add profile README and visual identity"
git remote add origin https://github.com/Buriedimp187/Buriedimp187.git
git push -u origin main
```
Check `git status` before committing: only the files in this folder should be listed.

## 6. Verify and set the avatar
1. Open `https://github.com/Buriedimp187`. The banner and README should appear above your pinned repositories.
2. Profile → Settings → Public profile → **Upload a photo** and choose `assets/logo/logo-mark-1024.png`. Avatars do not accept SVG.

## Later
Add a "Stack" or "Selected work" section to the README only after you have public repositories to back it up.
