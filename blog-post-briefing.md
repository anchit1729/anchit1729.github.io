# Blog Post Briefing

Use this briefing to continue work on the in-progress blog post in a fresh chat.

## Current Repo State

- Repository: `/Users/anchitmishra/Research/anchit1729.github.io`
- Current working branch: `codex/year-one-research-blog-post`
- Draft post path: `_posts/2026-05-15-year-one-research-map.md`
- Draft status: untracked, intentionally not committed yet
- The `master` branch has already been updated/deployed with recent site fixes:
  - removed visualization demo pages/assets
  - switched site typography to an SF-style system font stack
  - removed Devanagari homepage subtitle text
  - updated the public CV PDF
- This branch has been fast-forwarded to include those deployed changes.

## User Intent

The user wants to write a blog post dated May 15, 2026, reflecting on their research experience after year one. They want to keep adding to and shaping the post through chat.

Core themes the user named:

- research experience post year one
- now having "a map" of what to do
- working on multiple projects simultaneously
- reflecting on how the first year clarified direction
- likely balancing uncertainty, momentum, and project management
- traveling during a PhD, especially time spent in Paris
- finding a community to establish an identity within
- how AI has changed since the user's July 2025 post about LLMs and HCI research
- scoping reviews and methods in HCI
- pointing toward people, ideas, and papers that influenced the user's thinking during this period
- juggling research submission backlogs while pushing out new work
- moving from haptics toward information visualization, and how that shift affects early PhD work and research identity
- Paris internship connected to the user's first PhD paper, currently under review after one rejection
- Paris project broadened haptics for data representation from abstract/generic chart visualization toward situational awareness and control-room analytics
- first external PhD collaboration: Dr. Arnaud Prouzeau of the ILDA group at Inria Paris-Saclay, plus Nicolas and Marine Rouit-Leduc of Meaningful Design Studio
- collaboration involved a large wastewater treatment plant, one of the largest in the world, and future analytics systems for situational awareness in control rooms
- travel during graduate studies matters beyond conferences: exposure to research cultures and ideas, plus broader exposure to culture, art, and society
- Paris internship logistics took about eight months in the background: external travel grant application, Eurohaptics Society funding, Inria contribution for flight costs, security clearance for a government-affiliated research organization, and visa process
- Paris exposed both shared and different research cultures: shared sense of foundational information visualization work, but different project areas and infrastructure
- Inria visualization labs' work with large-scale collaborative displays prompted reflection on how HCI research can accumulate exclusivity through access to hardware platforms, institutions, partnerships, and deployment contexts
- User connects this exclusivity to other CS areas such as machine learning and large-scale distributed systems, where cutting-edge work can be gated by large organizations, money, equipment, and MoUs
- Work-life balance felt different in Paris/France compared with Canada, partly because Universite Paris-Saclay PhDs are closer to three years while Waterloo/Canadian PhDs are closer to four
- Collaboration felt genuinely interdisciplinary, with computer scientists, designers, and control room operators contributing to the design process
- User also wants to mention learning from Arnaud Prouzeau's experience with collaborative visual analytics, especially as a way to think beyond individual visualization interaction toward distributed sensemaking across people, displays, and roles
- User wants travel reflection to include Paris as a cultural hotspot and meaningful change of scenery after nearly four years living in Waterloo
- Paris helped the user feel immersed in French life: speaking French, living around French routines, working in a French research culture, and learning about French art and history
- Excursions beyond Paris also mattered: trip to the Copenhagen HCI group and meeting Tor-Salve Dalsgaard again, three years after last seeing him in Waterloo
- Copenhagen visit should support the idea that academia is a small bubble where people and ideas reappear across institutions; link Tor-Salve's website as https://torsalve.xyz/

## Existing Draft

The current draft has this front matter:

```yaml
---
layout: post
title: after year one, a map
date: 2026-05-15 11:32:16
description: reflections on finding a research direction after the first year and learning to work across multiple projects
tags: research phd
categories: general-posts
---
```

Current section structure:

- `Finding the shape of the work`
- `Having a map`
- `Working on several projects at once`
- `What has changed after year one`
- `What I want to do next`
- `Notes to keep expanding`

The draft is intentionally scaffold-like. It should preserve the user's reflective, plainspoken voice from prior posts, not become polished academic PR copy.

## Tone And Style

Match the user's existing blog tone:

- first-person, reflective, direct
- intellectually honest rather than overly triumphant
- comfortable with uncertainty
- grounded in research life and HCI work
- light, readable paragraphs
- avoid corporate/productivity language
- avoid sounding like a statement of purpose

Prior posts use casual phrasing and thoughtful transitions. The writing can be polished, but should still feel like the user thinking on the page.

## Likely Directions To Explore

Good prompts for expanding the post:

- What does "having a map" concretely mean?
- What projects are active, and how do they connect?
- What changed between "having interests" and "having a research direction"?
- What is hard about working on several projects at once?
- What practices help keep multiple projects from becoming scattered?
- How has the user's sense of research taste/judgment changed?
- What feels clearer after year one?
- What still feels unresolved?
- What would make year two successful?
- How did traveling, especially Paris, change the feeling of being in a PhD?
- What community does the user feel they are starting to belong to, and what identity does that make possible?
- Since the July 2025 post, has AI become less of a novelty topic and more of an ambient research condition?
- What have scoping reviews taught the user about HCI methods, research taste, and how fields organize knowledge?
- Which people, ideas, and papers have changed how the user thinks about the PhD at this stage?
- How do old submissions continue to occupy intellectual and logistical space while new work is beginning?
- What does it feel like to carry work from haptics into a newer information visualization research identity?
- How did the Paris internship make haptics-for-data feel more situated and less like an abstract chart-visualization question?
- What did working with Inria Paris-Saclay, Meaningful Design Studio, and a wastewater treatment plant teach the user about collaboration?
- How can the post argue for travel during graduate studies without making it sound like simple academic tourism?

Potential recurring idea:

> The goal is not that uncertainty disappeared, but that it has become organized enough to work with.

## Workflow Notes

- Do not commit the draft unless the user explicitly asks.
- Do not deploy this branch unless the user explicitly asks.
- Be careful not to include unrelated files in future commits.
- Local Jekyll build currently fails because the local Ruby/Bundler environment is missing the `jekyll` executable. GitHub Actions has been the reliable deployment/build path.
- If publishing later, remember the post date is `2026-05-15`. As of the current project date, this is in the past, so Jekyll should include it normally.

## Suggested Next Step

Ask the user for raw notes for one section at a time, then turn those notes into prose while keeping the section boundaries flexible. A good first section to expand is `Having a map`, because it anchors the whole post.
