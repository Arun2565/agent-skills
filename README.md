# Arun's Agent Skills

A collection of skills for AI coding agents. Skills packaged as SKILL.md files following the [Agent Skills](https://agentskills.io/) standard.

## Skills

- **annotated-reader** — Overlay MoonReader highlights on EPUB chapter text for re-reading (Apple Books style).
- **web-to-epub** — Convert YouTube videos, Substack transcripts, and web articles into EPUB ebooks.

## Installation

```bash
npx skills add arun2565/agent-skills
```

## Building

```bash
npm ci --ignore-scripts
node scripts/build-discovery-index.mjs https://raw.githubusercontent.com/arun2565/agent-skills/main/dist
```

## License

MIT
