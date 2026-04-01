# Claude Workspace

Cloud workspace for using Claude Code from any device — iPhone, browser, or Mac.

Powered by the **Claude GitHub App** (works with your claude.ai subscription).

---

## Setup (one-time)

Install the Claude GitHub App and connect it to this repo:
👉 https://github.com/apps/claude → Install → select `V77VV/claude-workspace`

---

## How to use @claude from your phone or browser

1. Go to [github.com/V77VV/claude-workspace/issues](https://github.com/V77VV/claude-workspace/issues)
2. Click **New issue**
3. Describe your task with `@claude`, e.g.:

   > @claude write a Python script that reads a CSV and plots a histogram

4. Submit — Claude responds within ~1 minute as a comment

## Example prompts

```
@claude write a Python function to parse a GROMACS .xvg file and return a pandas DataFrame

@claude create a matplotlib script to plot RMSD vs time from a CSV with columns: time, rmsd

@claude explain how to calculate RMSF using MDAnalysis and show an example
```

---

## How to use from Mac terminal

```bash
git clone https://github.com/V77VV/claude-workspace
cd claude-workspace
claude
```

Pull any files Claude created:
```bash
git pull
```
