# AGENTS.md

This repository is for recording thoughts about games and game design. It covers reflections that happen while playing games, making games, studying mechanics, or thinking through design problems.

## Language Policy

- Write this `AGENTS.md` and other agent-facing guidelines in English.
- Write all articles, notes, drafts, titles, summaries, tags, and Markdown prose in Chinese.
- Keep game titles, engine names, API names, code identifiers, file names, logs, and quoted source text in their original language when that is clearer.
- Do not translate Chinese game thoughts into English unless the user explicitly asks.

## Repository Content

- The main content is informal Chinese Markdown writing about games.
- Valid topics include play-session impressions, game design observations, mechanics analysis, level design thoughts, production notes, prototyping reflections, and postmortem-style notes from making games.
- Keep the writing centered on games and design. Avoid turning notes into unrelated personal journaling unless it directly supports the game-related thought.
- It is acceptable for articles to be subjective, speculative, unfinished, or exploratory. Preserve that character instead of over-polishing every note into a formal essay.

## Book Structure And Internal Links

- Treat the whole repository as a gradually growing book of Chinese game-design thoughts, not as a pile of isolated notes.
- Use English directory names throughout the repository.
- Put reusable concepts in the `concepts/` directory.
- Create a concept page only when a concept is actually used by an article or needed to clarify repeated terminology.
- When an article first uses a repository-specific concept, link to the relevant concept page with a relative Markdown link.
- Articles may link to other articles when one thought develops, challenges, or depends on another.
- Prefer meaningful internal links over repeated explanations. Do not duplicate long concept definitions inside every article.
- Keep concept pages concise and explanatory. They should define the term, clarify its usage, and point to related articles when useful.

## Markdown Writing Rules

- All articles must use Markdown files with the `.md` extension.
- Use Chinese headings for article structure.
- Prefer clear, natural Chinese prose.
- Use lists, blockquotes, tables, or diagrams only when they make the thought easier to follow.
- Do not add heavy metadata or front matter unless the repository already establishes a format or the user asks for it.
- If tags are used, write them in Chinese unless they are established game or technical terms.

## Article Readability

- Design paragraphs for comfortable Markdown reading.
- Prefer short paragraphs, with each paragraph carrying one observation, judgment, example, or transition.
- Avoid large walls of text.
- Use blank lines, Chinese section headings, and occasional lists when they improve reading rhythm.
- Do not force every article into the same template. Paragraph structure should serve the thought being written.

## Style Preferences

- Preserve the author's voice and original intent when editing existing notes.
- Keep observations concrete: mention the game situation, mechanic, feedback loop, level, system, or player behavior being discussed when possible.
- Separate play experience from design analysis when that improves clarity, but do not force a rigid template onto every article.
- Prefer concise edits over rewriting entire articles.
- Do not make the prose sound like marketing copy, a review score, or a wiki entry unless requested.

## File Organization

- Keep article file names readable and related to the note topic.
- Chinese file names are allowed and preferred for Chinese articles.
- Directory names must be written in English.
- If dates are used in file names, use a stable numeric format such as `YYYY-MM-DD`.
- When creating new game-thought articles, classify them into topic folders instead of placing every article at the repository root.
- Prefer a one-level folder structure for article categories. Examples include `play-notes/`, `reward-design/`, `mechanics-analysis/`, `level-design/`, and `production-notes/`.
- Do not create deeper nested folders unless the user explicitly asks or the repository already has a clear need for them.
- Do not invent complex folder structures before there is enough content to justify them.

## Agent Workflow

- Before creating or significantly rewriting an article, confirm the intended topic, tone, and scope if they are unclear.
- For small copy edits, preserve structure and meaning.
- For larger organization changes, explain the proposed structure before editing.
- Do not run git commands, create branches, commit, push, reset, or perform worktree operations unless the user explicitly asks.
- Do not install dependencies or introduce tooling unless the user explicitly approves it.
