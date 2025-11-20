# demo
---
layout: post
title:  "How I Set Up Two SSH Keys (Work & Personal)"
date:   2025-11-20 10:00:00 +0530
categories: ssh git tutorial
tags: [ssh,git,github]
---

This is a short how-to for setting up two SSH keys…

```bash
# sample code block
ssh-keygen -t ed25519 -C "personal@example.com"


### 4) Push to GitHub & enable Pages
```bash
git init
git add .
git commit -m "Initial blog"
# create repo on GitHub (use web UI or gh cli)
git remote add origin git@github.com:your-username/your-username.github.io.git
git push -u origin main
