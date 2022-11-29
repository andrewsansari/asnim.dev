+++
title = "Personal Tools"
date = "2022-11-09"
draft = false
+++



Software
- This website is hosted on GCP Storage bucket with Cloudflare in front.
- Editor: Vscode
- Terminal: Alacritty
- Notes: Notability

Hardware
- Laptop: Thinkpad p15v
- Phone: Pixel6
- Headphones: SonyXM3



Some extra tools I use
1. `delta` ( For Git diff)
Config
``
[core]
pager = delta

[interactive]
diffFilter = delta --color-only

[delta]
navigate = true    # use n and N to move between diff sections
light = false      # set to true if you're in a terminal w/ a light background color (e.g. the default macOS terminal)

[merge]
conflictstyle = diff3

[diff]
colorMoved = default
```