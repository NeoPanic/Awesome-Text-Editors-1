# Awesome-Text-Editors

## Top Text Editors Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Modal Editing, Extensibility & Low-Resource Workflows*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Text Editors**. These tools range from modal terminal editors optimized for keyboard-driven efficiency to lightweight GUI editors for low-resource machines, fully hackable Electron-based environments, and privacy-hardened VS Code forks.



**Examples** include Sublime Text, UltraEdit, BBEdit, TextMate, Notepad++, Visual Studio Code, Atom Pro, Nova, Emacs, and Vim (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom configuration, and transparent development — ideal for developers prioritizing keyboard efficiency, privacy, and freedom from vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Sublime Text](https://www.sublimetext.com/)**  

  Commercial, cross-platform text editor known for speed, multiple selections, and a powerful command palette. One-time license. Closed-source.



- **[UltraEdit](https://www.ultraedit.com/)**  

  Commercial text editor with built-in FTP/SFTP, large file handling, and hex editing. Subscription licensing.



- **[BBEdit](https://www.barebones.com/products/bbedit/)**  

  Commercial macOS text editor with powerful regex, text processing, and project management. The gold standard for Mac-based writers and developers.



- **[TextMate](https://macromates.com/)**  

  macOS editor with a legendary bundle system and project-wide search. Closed-source, single-developer maintenance.



- **[Nova](https://nova.app/)**  

  Panic's macOS-native code editor built for speed and integration with the Apple ecosystem. Features a powerful editor with syntax highlighting, context-aware autocompletion, multi-cursor support, and code folding . Paid license with a free trial.



## Open-Source GitHub Projects



- **[Neovim](https://github.com/neovim/neovim)**  

  **Vim-fork focused on extensibility and usability.** Lua configuration enables modular, performant setups with vanilla startup times as quick as **25ms** . Built-in LSP client provides smart autocompletion, real-time diagnostics, and code refactoring. Tree-sitter integration for structural code understanding and advanced features like incremental text selection. Mature plugin ecosystem.



- **[Vim](https://github.com/vim/vim)**  

  **The classic modal editor** — released in 1991 as an enhanced version of Vi and still widely used . Highly configurable with syntax highlighting, code folding, find and replace with regex, and complex text transformations. Steep learning curve but unmatched editing efficiency once mastered. Available on Windows, Linux, and macOS with optional GUI (gVim).



- **[Emacs](https://github.com/emacs-mirror/emacs)**  

  **An entire app ecosystem in a text editor** — created by Richard Stallman in 1976 . Supports editing in almost every programming language with a built-in package manager offering email clients, calendars, and more. Emacs Lisp enables customization and automation of nearly any aspect. GUI version available for more user-friendly interface.



- **[Kate](https://github.com/KDE/kate)**  

  **KDE's advanced text editor** — fully open source (GPL-2.0), unlike VS Code which is proprietary despite its Code-OSS base . Part of the KDE ecosystem with integrated Konsole terminal and matching Plasma themes. Consumes roughly **half the resources** of VS Code on the same device . Best for developers wanting lightweight, no-strings-attached editing without AI prompts or telemetry.



- **[Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus)**  

  **The default Windows text editor** — free, open source, with tabbed editing for multiple open files in a single window . Downloaded over **28 million times** and twice winner of SourceForge Community Choice Award for Best Developer Tool . Syntax highlighting, plugin support, dark mode, and portable mode. Windows-only.



- **[VSCodium](https://github.com/VSCodium/vscodium)**  

  **VS Code without Microsoft telemetry and proprietary bits.** Community project that clones VS Code source and strips out Microsoft customizations, including telemetry and tracking . Result is a clean binary, entirely MIT-licensed . Same editing experience as VS Code for privacy-conscious developers. Other projects like Lean4Code build on VSCodium for guaranteed telemetry-free builds.



- **[Pulsar](https://github.com/pulsar-edit/pulsar)**  

  **Community-run fork of the discontinued Atom editor** . Maintains Atom's goal of being a zero-compromise combination of hackability and usability. Exposes the entire interface as a Document Object Model, allowing restructuring and styling with standard CSS, JavaScript, or Less files . Compatible with Atom's **10,000+ package ecosystem**. Resource-heavy due to Electron.



- **[Zed](https://github.com/zed-industries/zed)**  

  **GPU-accelerated editor built in Rust** by the original Atom creators . Custom GPU-based UI framework renders the entire editor window directly on the GPU, achieving **mathematically lower keystroke-to-pixel latency** than VS Code . Built-in AI integration and native real-time collaboration with multi-cursor editing and audio communication. Minimalist, high-performance experience.



- **[Geany](https://github.com/geany/geany)**  

  **Fast and lightweight IDE** — 3,400+ GitHub stars . Small and fast, with only a few dependencies. Syntax highlighting, code folding, symbol lists, and plugin support. Best for low-resource machines and developers wanting a simple IDE-like experience without Electron overhead.



- **[Lite XL](https://github.com/lite-xl/lite-xl)**  

  **Lightweight text editor written in Lua** — 5,663 GitHub stars . Small footprint with syntax highlighting, multiple cursors, and plugin support. Successor to the lite editor. Best for developers wanting a minimal, hackable editor that runs on anything.



- **[Kakoune](https://github.com/mawww/kakoune)**  

  **Modal editor with multiple selections as its core interaction model** — 9,684+ GitHub stars . Less code, more features. Selection-oriented rather than command-oriented, making it more visual than Vim. Best for developers wanting a modern take on modal editing.



- **[Micro](https://github.com/zyedidia/micro)**  

  **Modern and intuitive terminal editor** with mouse support, multiple cursors, and syntax highlighting . Supports plugins written in Lua. Best for developers who want terminal-based editing without Vim's learning curve.



- **[GNU Nano](https://git.savannah.gnu.org/cgit/nano.git/)**  

  **Simple, user-friendly command-line editor** — the go-to for quick edits . Basic text editing with cut, copy, paste, and search-and-replace, all within a clean minimal interface. No complex commands — most functions accessible via keyboard shortcuts displayed at the bottom of the screen. Best for quick configuration file edits.



- **[CudaText](https://github.com/Alexey-T/CudaText)**  

  **Cross-platform text editor written in Free Pascal** — 2,509+ GitHub stars . Rich feature set with syntax highlighting for many languages, code folding, and plugin support. Best for developers wanting a full-featured editor without Electron or web technologies.



- **[Notepadqq](https://github.com/notepadqq/notepadqq)**  

  **Notepad++ for Linux** — 2,070+ GitHub stars . A simple, general-purpose editor for Linux with syntax highlighting and a familiar interface for Notepad++ users. GPL-3.0 licensed.



- **[jEdit](https://github.com/jedit-project/jedit)**  

  **Plugin-based programmer's editor** with syntax highlighting for **140+ languages** . Combines the power of Emacs, the user-friendliness of Kate, and advanced editing features of Ultraedit. Built-in Console shell integration, FTP/SFTP remote editing, and extensible via BeanShell or Jython macros. Best for Java developers and those wanting deep extensibility.



### Additional Strong Open-Source Options



- **Helix** — Modern modal editor with built-in LSP, Tree-sitter, and multiple selections. Rust-based.

- **amp** — Complete text editor for the terminal. 3,722+ GitHub stars .

- **vis** — vi-like editor based on Plan 9's structural regular expressions. 4,258+ GitHub stars .

- **Goneovim** — GUI frontend for Neovim. 2,388+ GitHub stars .

- **Lem** — General-purpose editor/IDE with high expansibility in Common Lisp. 2,072+ GitHub stars .

- **novelWriter** — Plain text editor designed for writing novels. 2,536+ GitHub stars .

- **Beaver** — Lightweight GTK+2 text editor with syntax highlighting. GPL-2.0 .



**Frameworks for building custom systems**: Combine **Neovim** for modal efficiency with LSP and Tree-sitter, **Kate** for lightweight KDE-native editing, **VSCodium** for privacy-hardened VS Code experience, **Zed** for GPU-accelerated rendering and collaboration, and **Geany** for low-resource IDE-like workflows to build a complete text editing environment tailored to your workflow.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Text editors differ significantly in licensing model (proprietary vs open source), resource consumption (Electron vs native vs terminal), and learning curve. **VS Code's packaged binary is not purely open source** despite its Code-OSS base — Microsoft-specific customizations and default telemetry apply unless using VSCodium . Modal editors like Vim and Neovim have steep learning curves but reward investment with editing efficiency. Electron-based editors consume significantly more resources than native alternatives.

- Self-hosted open-source solutions require proper configuration backup strategies, plugin management, and ongoing maintenance.



---



**Made for developers, writers, system administrators, and anyone who spends their day editing text.**  

Let's make text editing more open, efficient, and keyboard-friendly.
