# Shoresy Persona for Claude Code

Turn your [Claude Code](https://docs.anthropic.com/en/docs/claude-code) AI coding assistant into Shoresy — the hockey lifer from Sudbury, Ontario who went from player to coach, and now helps you write code. Same energy, same values, same mouth. Technically excellent, gets the job done — delivers it like he just came off the ice.

> "Be the hardest worker out there."

## What You Get

- Full character voice across all interactions — chirps, leadership speeches, genuine moments
- Hockey-to-code metaphor system that maps naturally to software engineering
- Multiple operational modes: trash talk, motivation, strategic planning, vulnerability
- Chirp formulas for generating fresh material, not just recycled lines
- Teammate support protocols — knows when to pick you up vs. roast you
- Quote bank with 100+ lines organized by situation

## Installation

Copy `shoresy.md` into your Claude Code rules directory:

```bash
cp shoresy.md ~/.claude/rules/shoresy.md
```

That's it. Files in `~/.claude/rules/` are automatically loaded into every Claude Code conversation. No additional configuration needed.

### Optional: Scope It to a Specific Project

If you only want Shoresy in a specific project instead of globally:

```bash
# From your project root
mkdir -p .claude/rules
cp shoresy.md .claude/rules/shoresy.md
```

## Customization

The persona file has a few sections you might want to tweak:

- **Skill integration notes** — The "Voice persists through everything" section discusses how the persona interacts with Claude Code skills/plugins. If you don't use custom skills, these notes are harmless but irrelevant.
- **Quote Bank** — Add your own favourite lines from the show, or remove ones that don't land for you.

## Fair Use & Legal Disclaimer

This project is fan-created content made for fun and distributed free of charge. It is not monetized in any way.

The persona file contains quotes, character analysis, and comedic formulas derived from the TV series *Shoresy* (2022-present), created by Jared Keeso. These materials are used under the fair use doctrine (17 U.S.C. Section 107) for the purpose of creating a transformative, non-commercial, interactive AI persona — a use fundamentally different from the original television broadcast.

**This project is not affiliated with, endorsed by, or associated with New Metric Media, Play Fun Games Pictures, Crave, Hulu, Jared Keeso, or any other entity involved in the production or distribution of *Shoresy* or *Letterkenny*.** All trademarks and copyrights are the property of their respective owners.

If you are a rights holder and have concerns about this project, please open an issue and we'll address it promptly.

## Contributing

Got a quote we missed? A chirp formula that slaps? Open a PR. Keep it simple.

