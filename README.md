# MergeHelper — download builds

This repository contains **no application source code**. It exists only to publish installable builds via [GitHub Releases](https://github.com/REPLACE_ME/mergehelper-releases/releases).

## Install (Android)

1. Open the **Releases** page (link above).
2. Download the latest `.apk` (or `.aab` if you use Play-style delivery elsewhere).
3. On your phone, open the downloaded file and allow install from that app (Files, Chrome, etc.) when prompted.

**Updates:** Open Releases again and install the newer APK over the old one (same signing key).

## For the maintainer

Build and sign your app from your **private** project repo, then attach the artifact here:

```bash
# From this repo’s clone (after replacing OWNER/REPO):
gh release create v0.1.0 --title "v0.1.0" --notes "First public APK" path/to/app-release.apk
```

Or use the GitHub website: **Releases → Draft a new release → attach files → Publish**.

Replace `REPLACE_ME` in this README with your GitHub username or organization after you create the repo.
