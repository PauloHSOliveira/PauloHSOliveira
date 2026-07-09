# GitHub Profile Improvement Checklist

Manual settings and actions to verify after the README update.

---

## 1. Enable Private Contribution Visibility

This ensures your work on private/company repositories appears in your contribution graph.

- [ ] Go to [GitHub Settings > Public profile](https://github.com/settings/profile)
- [ ] Scroll to **Contributions & Activity**
- [ ] Enable **Include private contributions on my profile**

---

## 2. Add All Commit Emails to GitHub

Contributions made from emails not linked to your account won't appear in your graph.

- [ ] Go to [GitHub Settings > Emails](https://github.com/settings/emails)
- [ ] Add your personal email: `contato@pholiveira.dev`
- [ ] Add your work email if you commit from a different address at Popstand
- [ ] Add your GitHub noreply email if you use it (format: `ID+username@users.noreply.github.com`)
- [ ] Verify all emails are confirmed

---

## 3. Review Pinned Repositories

- [ ] Keep **ScaleCraft-Network** pinned (Rust/blockchain focus is a good differentiator)
- [ ] Keep **clicksign-library** pinned (real TypeScript library with practical value)
- [ ] Review **new-portfolio** — only keep pinned if the README and deployed site are polished
- [ ] Consider creating public showcase repos for technical depth:
  - `case-study-design-editor` — architecture decisions, component design
  - `case-study-saas-admin-platform` — technical write-up, no confidential data
  - `case-study-api-architecture` — API design patterns, diagrams, lessons learned

---

## 4. Improve Repository Descriptions

Short descriptions appear in pinned repos and search. Make them count.

- [ ] **ScaleCraft-Network**: `Blockchain ecosystem built with Rust — distributed systems and scalable network architecture`
- [ ] **clicksign-library**: `TypeScript library for the ClickSign REST API — typed, functional, and production-ready`
- [ ] **new-portfolio**: `Personal portfolio and engineering website — pholiveira.dev`

---

## 5. GitHub Profile Settings

- [ ] Verify profile name is set to `Paulo Oliveira`
- [ ] Verify bio is set to `Senior Software Engineer at Popstand`
- [ ] Add location: `Belo Horizonte, Brazil`
- [ ] Add website: `https://pholiveira.dev`
- [ ] Enable **Show account achievements on my profile** if desired

---

## 6. Optional: Custom Stats Workflow

A GitHub Actions workflow is available at `.github/workflows/update-profile.yml` in this repository.

To enable it:

- [ ] Go to [Settings > Secrets and variables > Actions](https://github.com/PauloHSOliveira/PauloHSOliveira/settings/secrets/actions)
- [ ] Create a secret named `PROFILE_STATS_TOKEN`
- [ ] Use a [Personal Access Token](https://github.com/settings/tokens) with `read:user` scope
- [ ] Run the workflow manually from the **Actions** tab to test it
- [ ] Verify the generated files are committed to the `assets/` directory

---

## 7. Contribution Graph Health

- [ ] Confirm your primary development email matches a GitHub-registered email
- [ ] If using a work Git config at Popstand, verify that email is also added to GitHub
- [ ] Check [github.com/PauloHSOliveira](https://github.com/PauloHSOliveira) to confirm private contributions are visible

---

_Last updated: 2026-07-09_
