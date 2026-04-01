# Claude Workspace

This is a cloud workspace for using Claude Code from any device — iPhone, browser, or Mac terminal.

## How to use @claude from your phone

1. Open [github.com/V77VV/claude-workspace](https://github.com/V77VV/claude-workspace) in your browser
2. Click **Issues** → **New issue**
3. Describe your task and mention `@claude` anywhere in the body, e.g.:

   > @claude write a Python script that reads a CSV file and plots a histogram

4. Submit the issue — Claude will run automatically and post results as a comment (usually within ~1 minute)

## Examples

```
@claude write a Python function to parse a GROMACS .xvg file and return a pandas DataFrame

@claude create a matplotlib script to plot RMSD vs time with error shading

@claude explain what MDAnalysis Universe object is and show a usage example
```

## How to use from Mac terminal

Clone this repo and work locally with Claude Code:

```bash
git clone https://github.com/V77VV/claude-workspace
cd claude-workspace
claude
```

## Notes
- Results are pushed as commits to this repo automatically
- You can review and pull changes to your Mac with `git pull`
- The Claude GitHub App must be installed: [github.com/apps/claude](https://github.com/apps/claude)
