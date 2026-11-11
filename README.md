# VoxNote agent skills

Agent skill that teaches AI agents (Claude Code, Cursor, Codex and others) how to read your phone calls, voicemails, transcripts and summaries from [VoxNote](https://voxnote.ai) through its MCP server.

## Install

```bash
npx skills add VoxNoteSoftwares/voxnote-skills
```

Then connect the MCP server:

```bash
claude mcp add --transport http voxnote https://api.voxnote.ai/mcp
```

Requires a VoxNote Essential or Pro plan.

## Skills

- [`voxnote`](skills/voxnote/SKILL.md): list calls, read summaries and transcripts, find contacts, handle pagination and errors.

## License

MIT
