---
title: "Why I Started This Blog"
date: 2026-02-17
draft: false
summary: "What this blog is about, why I built it with Hugo instead of WordPress, and what you can expect to find here."
tags: ["meta", "hugo", "career"]
---

## The Short Version

I wanted a place to write about cybersecurity, AI, books am reading and things I'm learning -- without fighting a CMS to do it.

## Why a Blog at All?

If you work in tech, you've probably heard the advice: *"Write about what you're learning."* I resisted it for a while - there are already plenty of infosec blogs. But I realised the blog isn't really for an audience -- it's for me.

Writing forces you to organise your thoughts. If you can explain something clearly in a blog post, you probably actually understand it. And if you can't, that's a signal to go back and study.

So this blog is part notebook, part portfolio, and part accountability system.

## Why Hugo Over WordPress

I ran this site on WordPress.com for a while. I managed to get it up and running but that was it, there was a lot of friction getting the site to behave the way I wanted it. So with the help of Claude I decided on:

- **Markdown**: I already write everything in Obsidian using Markdown. WordPress wants its block editor. Hugo posts are just `.md` files -- I write them the same way I write my notes.
- **Git workflow**: Every change is a commit. I can see the full history of the site, roll back mistakes, and branch for experiments.
- **No attack surface**: There's no database, no PHP, no plugins to patch. The site is static HTML served from a CDN.
- **Free hosting**: GitHub Pages is free. No WordPress plan, no renewal surprises.
- **Learning opportunity**: Building this site I'm learning about CI/CD (GitHub Actions), DNS, HTML/CSS, and Git workflows. WordPress taught me how to click buttons.

## What to Expect

I plan to write about:

- **Cybersecurity**: Things I'm learning, tools I'm using, concepts that clicked
- **AI**: I've been experimenting with AI agents, Local LLMs, AI assistants and deepfakes
- **Books**: I'll be posting a short review of books I read this year, aiming for 6
- **Tech**: Whatever I'm currently tinkering with, usually homelab stuff

No posting schedule, no SEO games. Just writing when I feel like it.

## The Stack

For the curious:

- **Generator**: [Hugo](https://gohugo.io/) (static site generator written in Go)
- **Theme**: [PaperMod](https://github.com/adityatelange/hugo-PaperMod) (clean, fast, dark mode)
- **Hosting**: GitHub Pages (free, served via CDN)
- **Deployment**: GitHub Actions (auto-builds on every push to `main`)
- **Domain**: bryanlopez.net (pointed via DNS)
- **Writing**: Markdown in VS Code or Obsidian


If you want to build something similar, all the source code is on [GitHub](https://github.com/cauca-research/myblog).
