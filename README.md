# Doppy AI

This is a project I'm working on when I have time. Since time is limited, I'm not sure how frequent what will be. I'm building this project to solve a certain issue I've recently faced. I'm not sure where this project will go right now. I'm just making it for myself. However, depending on how well it turns out, it'd be cool to release as tool for others. We'll see!

> _Fun fact:_ the name "Doppy" comes from the name of my [custom Gemini gem](https://gemini.google/overview/gems/) which I've used throughout college to help me learn & study.

## Issue

AI is an incredibly useful tool for learning. It's an excellent resource & for many, it's a drop-in tutor for whenever you've got questions. However, when working with **newer** or **niche** tools, AI is more prone to hallucinate junk information. 

I really like the _C3_ programming langauge. It's so cool. I'm also making a project with _Deno Fwoosh, Deply, & KV_. All of these tools are very young, as a result of that, LLMs do not have them indexed well. I initially overcame that hurdle by cloning the documentation locally & using them as a rudimentary knowledge base. It works, but set up is really annoying.

## Solution

I want to build an AI Desktop tool that tracks documentation of young/poorly indexed projects. The users would be able to get a new knowledge base by attaching a GitHub repo link. The program would then clone the repo & feed the underlying model the docs. The user could also trigger an update where the tool would go through each repo & simply run `git pull`.

In my mind, this will be like a local-first tool that acts like an agile & specialized [NotebookLLM](https://notebooklm.google).
