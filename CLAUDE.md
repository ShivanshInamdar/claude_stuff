# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a general prototyping and sandbox repository for ad-hoc scripts, experiments, and miscellaneous files. It serves as a flexible workspace for:

- Quick Python scripts and prototypes
- Markdown documents and notes
- Experimental code that doesn't belong in other projects
- Reference materials and documentation
- Any other ad-hoc content

## Structure

There is no fixed structure. Files and directories are organized as needed for each specific task or experiment.

## Python Environment

When Python scripts are added, they can be run directly without a specific build process:

```bash
python script_name.py          # Run a Python script
python3 script_name.py         # Use Python 3 explicitly if needed
```

For scripts requiring dependencies, consider:
- Using a virtual environment: `python -m venv venv && source venv/bin/activate`
- Installing dependencies: `pip install <package>`
- Or documenting dependencies in comments at the top of each script

## Notes

- This repository intentionally has no formal structure or build system
- Each script or document should be self-contained where possible
- Feel free to create subdirectories to organize related experiments
