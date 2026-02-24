# CobblrSH README

Adds fully featured syntax highlighting for my custom language Cobblr! It should be totally compatible with any VSCode editor and there are no co-dependencies.

## Features

Simple syntax highlighting that should be compatible with the custom color schemes.

> Note: LSP In Progess!

## Requirements

No external requirements

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something. -->

## Known Issues

There are likely some bugs as this is my first extension. If there are any, please open a discussion board on this repo.

## Release Notes

As of this release, the language is not fully functional, but the tokenizer and parser and this syntax highlighter are working with a type-checker on the way and a compiler to LLVM-IR shortly thereafter.

### 1.0.0

Initial release of CobblrSH

## Install CobblrSH

Since Cobblr is currently in active development and not yet on the VS Code Marketplace, you can install the extension manually using the **VSIX** method—it's the cleanest way to get up and running.

1. **Download** the `.vsix` file from the [Releases](your-github-link-here) page.
2. Open **Visual Studio Code**.
3. Open the **Extensions** view (click the Extensions icon on the left or press `Ctrl+Shift+X`).
4. Click the **`...`** (More Actions) menu in the top-right corner of the Extensions pane.
5. Select **Install from VSIX...** and select the downloaded file.
6. **Restart** VS Code if prompted.

---

### Alternative: Command Line (Fastest)
If you have the VS Code CLI in your path, simply navigate to your download folder and run:

```bash
code --install-extension cobblrsh-1.0.0.vsix

**