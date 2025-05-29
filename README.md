# DGL Syntax Highlighting for Visual Studio Code

This extension provides syntax highlighting for `.dgl` files written in **DiaLogUE** language.

## About

`.dgl` files are plain text dialogue scripts designed for use with a custom **Dialogue Plugin** for Unreal Engine (currently in development). This plugin parses `.dgl` text files following the DiaLogUE language rules and converts them into DataAssets. These DataAssets can then be utilised within Unreal Engine's dialogue system to create interactive narratives.

This syntax highlighting makes editing `.dgl` files easier by visually distinguishing keywords, strings, comments, speaker names, and numbers.

## Features

- Highlights DiaLogUE language keywords such as `[choice]`, `[branch]`, `[set]`, `[condition]`, `[goto]`, `[summary]`, and `[fork]`.
- Highlights speaker names before dialogue lines.
- Highlights strings, comments (lines starting with `#`), and numeric literals.
- Supports the `.dgl` file extension.

## Installation

1. Switch to **packages** branch in this repository
2. Download the desired version `.vsix` package and install via **Extensions: Install from VSIX...** in Visual Studio Code.

## Usage

Simply open `.dgl` files in Visual Studio Code. The syntax highlighting will be applied automatically, making writing and maintaining your dialogue scripts easier.

---

Created for the **DiaLogUE** Unreal Engine dialogue plugin to improve the authoring experience. Link: https://github.com/wortback/DialogueSystem

---

If you find any issues or want to contribute, please open an issue or pull request on the repository.

**Enjoy!**
