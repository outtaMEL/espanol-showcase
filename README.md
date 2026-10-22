# Español Fácil

**Making Spanish video usable for a beginner learning through comprehensible input.**

Personal product project by Fan Niu. Product concept, feature direction and iterative review were my contribution; implementation was primarily completed with AI assistance.

![Español study workspace with video and bilingual transcript](assets/study-workspace.jpg)

*Video and bilingual transcript share one workspace, with language-support tools available alongside the content.*

## Why I built it

I wanted to learn Spanish through comprehensible input: learning from meaningful content in the language. At the beginner stage, however, my vocabulary and familiarity with sentence structure, grammar and verb tenses were not yet sufficient to understand much of a video. Watching authentic content alone often left too much of it inaccessible.

I had not found a tool that brought the language support I needed together with the videos I wanted to watch. I built Español to keep real content at the centre of learning, with help for unfamiliar words, sentences, grammar and tenses available in context.

## The learning flow

1. Bring a chosen Spanish video into the workspace.
2. Follow the video with a Spanish–English transcript.
3. Inspect unfamiliar language through contextual lookup, sentence explanations and verb reference.
4. Continue watching, with the material more accessible than it was before.

![Existing sentence explanation with word breakdown and a follow-up question](assets/context-explanation.jpg)

*An existing explanation connects the transcript sentence with a word-by-word breakdown and follow-up discussion. Here, the learner asks whether **tan** changes with gender; the response explains how it differs from **tanto/a/os/as**. The explanation is shown in Chinese in this personal study setup.*

## Iterating around continuity

As my study progressed, I added connections to earlier material. “Visto antes” review links a word to examples from content already encountered, distinguishes the clicked form from related inflections, and keeps a route back to the original study session.

Recent iterations refined subtitle timing, lookup-state preservation, word-history updates and episode-tab behaviour. These details support the same goal: moving between video, language support and previous examples without losing the learning context.

## Current stage and implementation

Español is a personal project run locally on desktop. The account of its usefulness comes from my own learning experience.

The application uses JavaScript ES modules, Python/Flask, JSON data and a SQLite runtime layer. AI services support transcription, translation, dictionary lookup and explanations.
