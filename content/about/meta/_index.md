---
title: Meta (Site Info)
date: 2024-11-30T21:10:00.000-0600
menus: about
---
This site is built on [Hugo](https://gohugo.io), a very flexible static site generator, and [Turbo](https://turbo.hotwired.dev), which drastically speeds up page load times by only reloading what changes (and not rerunning JS that's already been run).

It aims to capture the vibes of the old internet (heavily customized homepages with busy, flashy designs and fun widgets) while still having very quick load times and not hogging your computer's resources.

## last commit

<p id="message">Loading last commit info...</p>
<script>
  fetch('https://api.github.com/repos/coffeeknife/homepage/commits?per_page=1')
  .then(res => res.json())
  .then(res => {
    document.getElementById('message').innerHTML = res[0].commit.author.date + '<br>' + res[0].commit.message
  })
</script>

Repo at <a href="https://github.com/coffeeknife/homepage"><i class="fa-brands fa-github"></i> GitHub</a>

# Tod

- mobile css (this page is a nightmare on mobile rn)
- add my own player controls to the youtube embed
- rearrange sections; have general media tab instead of separate music/gaming/etc
- recreate album grid from my old neocities, now with a click action to start playing my favorite song off each album
- make tech setup and homelab pages, maybe figure out how to expose stats or something fun
- make script for quickly generating new (blank) blog posts, start blogging on here

# Page Ideas
- firefox extensions/config