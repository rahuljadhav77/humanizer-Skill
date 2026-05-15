# humanizer-Skill

A skill for Claude Code and OpenCode that removes signs of AI-generated writing from text, making it sound more natural and human.

Based on the original [humanizer](https://github.com/blader/humanizer) by blader.

## Files

- **SKILL.md** - The main skill file with prompt and instructions
- **WARP.md** - Word and pattern reference guide
- **LICENSE** - License information (MIT)

## Installation

### Claude Code
```bash
mkdir -p ~/.claude/skills
git clone https://github.com/rahuljadhav77/humanizer-Skill.git ~/.claude/skills/humanizer
```

### OpenCode
```bash
mkdir -p ~/.config/opencode/skills
git clone https://github.com/rahuljadhav77/humanizer-Skill.git ~/.config/opencode/skills/humanizer
```

## Usage

```
/humanizer

[paste your text here]
```