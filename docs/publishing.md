# Publish this package to GitHub

This repository package is prepared but **not automatically published**. To create the online repository, the owner must use GitHub account access that permits repository creation.

## Recommended repository metadata

- **Owner:** `rachmatefendi`
- **Name:** `adaptive-deep-research-prompt`
- **Description:** `Adaptive evidence-driven deep research prompt with autonomous intake, source verification, critical analysis, and governance-aware reporting.`
- **Website:** `https://rachmatefendi.com`
- **Initial release:** `v1.0`
- **Suggested topics:** `deep-research`, `prompt-engineering`, `research-methodology`, `evidence-based`, `llm`, `research`, `ai-governance`, `decision-support`, `source-verification`.
- **Visibility:** Decide explicitly (`private` is the safer staging default).
- **License:** No license selected. Do not claim open-source reuse until the author chooses a license.

## Publish using GitHub website and Git CLI

1. Create an **empty** repository at https://github.com/new using the owner and name above. Do not initialize it with a README, license, or .gitignore if following the commands below.
2. Unpack the repository archive on your machine.
3. Run the following commands in the unpacked `adaptive-deep-research-prompt/` directory, using your own configured Git identity and authenticated GitHub access:

```bash
git init -b main
git add .
git commit -m "docs: initial adaptive deep research prompt v1.0"
git remote add origin git@github.com:rachmatefendi/adaptive-deep-research-prompt.git
git push -u origin main
git tag -a v1.0 -m "Initial repository release v1.0"
git push origin v1.0
```

If HTTPS authentication is preferred, change the origin to `https://github.com/rachmatefendi/adaptive-deep-research-prompt.git`.

4. Add repository description, website, and topics in GitHub Settings / About.
5. Verify the README, canonical prompt, eight examples, and tag are present.
6. Choose a publication license separately before inviting broad reuse. If made public without a license, the published content remains under its applicable copyright restrictions.

**Note:** These commands are instructions, not evidence of an online repository, commit, tag, or release being created.
