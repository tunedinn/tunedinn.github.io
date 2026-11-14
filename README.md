# TunedInn Website (`tunedinn.github.io`)

The official GitHub Pages site for **TunedInn** — practical Microsoft Intune scripts, Proactive Remediations, Autopilot guides, and YouTube walkthroughs.

**Live site:** [https://tunedinn.github.io](https://tunedinn.github.io)

## Adding a New Guide
Create a Markdown file in `_posts/` named `YYYY-MM-DD-your-slug.md` with front matter:

```yaml
---
layout: post
title: "Your Guide Title"
date: 2026-11-14
category: Remediations   # Remediations | Scripts | Autopilot | Help Desk
audience: All Admins     # Help Desk | Intermediate | Senior Admins | All Admins
description: "Short summary of what this solves."
github_url: "https://github.com/tunedinn/intune-remediations/tree/main/Your-Folder"
---
```

To embed a YouTube walkthrough anywhere in the post:

```liquid
{% raw %}{% include youtube.html id="YOUR_YOUTUBE_VIDEO_ID" %}{% endraw %}
```