# WilsonSpeak Knowledge Hub

A lightweight Traditional Chinese static site for WilsonSpeak video companion articles and topic discovery. It is designed for GitHub Pages and needs no build step.

## Publish with GitHub Pages

1. Push the repository to the `main` branch.
2. In GitHub, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
3. The workflow in `.github/workflows/pages.yml` publishes the repository root after each push.

The repo currently has no official WilsonSpeak article or confirmed video links. Add each article as its own HTML page and replace the topic search links with exact video URLs as those are selected. Do not leave generic channel-search links as article links.
