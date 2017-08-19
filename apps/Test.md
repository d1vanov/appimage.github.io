---
layout: app
created: 2017-04-15
updated: 2017-04-15

permalink: /Test/
title_obvious: true
generic: Generic title goes here
description: Description goes here
license: License goes here

authors:
  - name: GitHub username goes here
    url: GitHub repo goes here

links:
  - type: Web
    url: WebUrlGoesHere
  - type: GitHub
    url: GitHubUrlGoesHere
  # Link to website with install instructions
  - type: Install
    url: GitHubReleasesPageGoesHere
  # Screenshots, videos, reviews
  - type: Screenshots
    url: https://appimage.github.io/AppImageHub/database/Cantata/screenshot.jpg

screenshots:
  - /database/Cantata/screenshot.jpg

# TODO: This needs to be replaced by channels
installation:
  - system: AppImage
    info:
    - version: '0.3'
      repository: 'ppa:justsomedood/justsomeAppImage'
      package: pack
      type: stable
    - version: '0.2'
      repository: repo
      package: pack
      type: unstable
  - system: Ubuntu
    info:
    - version: '14.04'
      repository: ppaxy
      package: pack
      type: daily

tags:
  - official 
---