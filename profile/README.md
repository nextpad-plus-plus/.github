<p align="center">
  <a href="https://nextpad.org/">
    <img src="https://raw.githubusercontent.com/nextpad-plus-plus/nextpad.org/main/assets/images/screenshot7.png" alt="Notepad++ for macOS" width="800">
  </a>
</p>

<h1 align="center">Nextpad++ for macOS</h1>

<p align="center">Nextpad++ is an independent port of Notepad++ for Apple Silicon and Intel Macs, now running natively on your Mac. </p>

<p align="center">
  <a href="https://nextpad.org/download/">Download</a> &middot;
  <a href="https://nextpad.org/">Website</a> &middot;
  <a href="https://github.com/nextpad-plus-plus/nextpad-plus-plus-macos">Source</a> &middot;
  <a href="https://nextpad.org/plugins/">Plugins</a> &middot;
  <a href="https://nextpad.org/donate/">Donate</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-11%2B-blue" alt="macOS 11+">
  <img src="https://img.shields.io/badge/arch-Apple%20Silicon%20%7C%20Intel-green" alt="Apple Silicon and Intel">
  <img src="https://img.shields.io/badge/license-GPL--3.0-orange" alt="GPL-3.0">
</p>

---

## About this organization

This organization hosts the **native port of [Notepad++](https://notepad-plus-plus.org) to macOS** — a full port of the original codebase, built to run as a first-class native Mac application. No Wine, no Porting Kit, no compatibility layer. Just Nextpad++, on your Mac.

Our goal isn't to make Notepad++ "run" on Mac. It's to make it feel like it *belongs* there — with native menus, shortcuts, dark mode, and system integration — while keeping everything developers love about the original.

## Our projects

### Core

| Repository | Description |
|---|---|
| **[nextpad-plus-plus-macos](https://github.com/nextpad-plus-plus/nextpad-plus-plus-macos)** | The main app — full native port of Notepad++ to macOS |
| **[nextpad-plus-plus.org](https://github.com/nextpad-plus-plus/nextpad.org)** | Source for the official project website |
| **[nppPluginList](https://github.com/nextpad-plus-plus/nppPluginList)** | Plugin registry — universal (arm64 + x86_64) dylib plugins for the macOS port |

### Ported plugins

| Repository | Description |
|---|---|
| **[ComparePlus](https://github.com/nextpad-plus-plus/ComparePlus)** | File comparison — diff two documents side by side |
| **[DoxyIt](https://github.com/nextpad-plus-plus/DoxyIt)** | Doxygen comment generator for C/C++/PHP/Python |
| **[ElasticTabstops](https://github.com/nextpad-plus-plus/ElasticTabstops)** | Elastic tabstops — columns auto-align as you type |
| **[FoldingLineHider](https://github.com/nextpad-plus-plus/FoldingLineHider)** | Visually hide the contents of folded code blocks |
| **[indentbyfold](https://github.com/nextpad-plus-plus/indentbyfold)** | Auto-indent based on fold level — useful for nested structures |
| **[JSON-Viewer](https://github.com/nextpad-plus-plus/JSON-Viewer)** | JSON syntax check, format, and tree view |
| **[notepadpp_rpc](https://github.com/nextpad-plus-plus/notepadpp_rpc)** | Discord Rich Presence — show what you're editing |
| **[NPP_ExportPlugin](https://github.com/nextpad-plus-plus/NPP_ExportPlugin)** | Export the current document to RTF or HTML, preserving syntax colors |
| **[NppAIAssistant](https://github.com/nextpad-plus-plus/NppAIAssistant)** | In-editor AI assistant pane — chat with multiple LLMs side by side with the code |
| **[nppAutoDetectIndent](https://github.com/nextpad-plus-plus/nppAutoDetectIndent)** | Detect and apply existing indentation style on file open |
| **[NppBeads](https://github.com/nextpad-plus-plus/NppBeads)** | Beads issue tracker integration — view, create, and edit issues without leaving the editor |
| **[nppfavorites](https://github.com/nextpad-plus-plus/nppfavorites)** | Favorites / bookmarks for files and folders |
| **[NppLLM](https://github.com/nextpad-plus-plus/NppLLM)** | Send selected text to OpenAI / Claude / Ollama / LM Studio / Groq / OpenRouter / Azure / vLLM / LocalAI / AnythingLLM — wire-compatible with NppOpenAI |
| **[NppMarkdownPanel](https://github.com/nextpad-plus-plus/NppMarkdownPanel)** | Live Markdown preview side panel with synced scrolling |
| **[NppPluginOpenHost](https://github.com/nextpad-plus-plus/NppPluginOpenHost)** | One-click open of `/etc/hosts` (with sudo elevation as needed) |
| **[nppQuickText](https://github.com/nextpad-plus-plus/nppQuickText)** | Tab-triggered text snippets / abbreviations expansion |
| **[nppURLPlugin](https://github.com/nextpad-plus-plus/nppURLPlugin)** | URL encode / decode the current selection |
| **[pork2sausage](https://github.com/nextpad-plus-plus/pork2sausage)** | Pork to Sausage — bulk text transformations on selection |
| **[qkNppReverseLines](https://github.com/nextpad-plus-plus/qkNppReverseLines)** | Reverse the order of lines in the current selection |
| **[selectquotedtext](https://github.com/nextpad-plus-plus/selectquotedtext)** | Select the text inside the nearest pair of quotes / brackets |
| **[SelectToClipboard](https://github.com/nextpad-plus-plus/SelectToClipboard)** | Copy the current selection to clipboard with one shortcut |
| **[XmlNavigator](https://github.com/nextpad-plus-plus/XmlNavigator)** | XML tree navigator side panel — jump between nodes |
| **[xmltools](https://github.com/nextpad-plus-plus/xmltools)** | XML toolkit — validate, pretty-print, XPath, XSLT, schema check |

## Everything you love, on your Mac

| | Feature | Description |
|---|---|---|
| `</>` | **Syntax Highlighting** | 80+ programming languages with customizable themes |
| :gear: | **Plugin Ecosystem** | A growing set of plugins ported from Windows |
| :zap: | **Apple Silicon Native** | Built for M-series chips. Runs efficient on battery |
| :mag: | **Search & Replace** | Regex, find-in-files, bookmarks, incremental search |
| :arrow_left_hook: | **Split View** | Edit two documents (or two parts of one) side by side |
| :play_or_pause_button: | **Macro Recording** | Record and replay repetitive editing tasks |
| :globe_with_meridians: | **137 Languages** | Switch the UI to your preferred language |

## Credits

Nextpad++ for macOS is built directly upon the work of **[Don Ho](https://github.com/donho)**, the original author and principal developer of [Notepad++](https://notepad.org). For over two decades, Don has maintained Notepad++ as a free, open-source project loved by millions of developers. This port would not exist without his extraordinary work.

The macOS port is developed by **[Andrey Letov](https://github.com/aletik)** ([aletik.me](https://aletik.me)).

---

<p align="center">
  Version 1.0.5 &middot; Apple Silicon & Intel &middot; macOS 11+<br>
  <a href="https://www.gnu.org/licenses/gpl-3.0.html">GPL-3.0 License</a>
</p>
