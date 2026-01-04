---
title: "AI Auto Blog"
date: 2023-04-11T7:15:00+01:00
draft: false
tags: ["by gh", "automation", "gpt", "openai", "github actions"]
url: posts/ai-auto-blog
showToc: true
tocOpen: false
showReadingTime: true
showWordCount: true
cover:
    image: "https://user-images.githubusercontent.com/35503959/230745225-232c810b-0abf-4dfa-9261-2c707354691a.png#center"
    alt: "wise owl"
    hidden: false
---

> Note: This experiment ran for three years and ended on 2026-01-04; all auto-generated content has been [removed](https://github.com/ghillb/ghillb.github.io/commit/883082e).

## TL;DR
The *AI Auto Blog* is a fun project of mine that leverages LLM APIs and scheduled CI/CD to autonomously generate and publish daily GPT-enhanced summaries about the field of AI. 

Theoretically, it will keep producing content until one of the services fails or disappears. However, we may mitigate this shortcoming with the addition of a robo-maintainer in the future.

The auto-generated summaries can be accessed with the ["daily ai summary"](/tags/daily-ai-summary/) tag.

## Requirements
- The bot must generate and post content entirely autonomously
- The content should be at least somewhat relevant to my interests
- The maintenance and cost should be kept to an absolute minimum

## Implementation
To meet the requirement of low cost and maintenance, I opted not to establish my own infrastructure and relied solely on managed APIs and CI/CD services. As such, I chose to utilize [GitHub Actions](https://github.com/features/actions) to orchestrate the generation and distribution of content. The workflow is relatively straightforward: 

1. The seed for the content is collected from recent online discussions
1. The content is generated with [OpenAI's](https://platform.openai.com/docs) `gpt-3.5-turbo` model
1. The posts (and the whole site) are created with [Hugo](https://gohugo.io/)
1. The result is pushed to the repo and published via [GitHub Pages](https://pages.github.com/)

## Thoughts on Auto-Generated Content
AI-assisted blogs with autonomously generated content like this one are still a rarity in early 2023. However, their numbers are likely to increase as tools for building them become more capable and less complex, while the quality of generated content improves.

Predicting the scale of auto-generated online content is no easy task, but it's safe to assume that autonomous agents are likely to surpass humans in terms of sheer volume. This is already evident in text-based online discussions. As these agents evolve, they may even begin replicating and refining themselves, leading to an even more rapid acceleration of this trend.

Without intervention to moderate certain platforms, it is possible, that content created by humans will become the rarity.

## Roadmap
- Incorporate automatic image generation to give the posts a little more flair
- Enhance the quality of the generated content in general 
- Implement auto-maintaining in the future to keep the bot running smoothly
