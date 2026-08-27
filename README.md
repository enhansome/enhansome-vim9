<div align=center>

<img src="assets/vim-logo.svg" alt="Vim Logo" width="120" height="120">

# Awesome-Vim9 with stars

Welcome to Awesome Vim9, a community-driven list of useful vim9script powered plugins, utilities, and libraries. Legacy vimscript plugins are not listed here.

To submit a new plugin read [CONTRIBUTING.md](./CONTRIBUTING.md) first.

</div>

***

* [AI Assistants](#ai-assistants)
* [Color Scheme](#color-scheme)
* [Command Execution](#command-execution)
* [Completion](#completion)
* [Editing](#editing)
* [File Management](#file-management)
* [Fuzzy Finding](#fuzzy-finding)
* [Games](#games)
* [Guides](#guides)
* [Integrations](#integrations)
* [Language Server Protocol](#language-server-protocol)
* [Libraries](#libraries)
* [Markdown](#markdown)
* [Miscellaneous](#miscellaneous)
* [Motion](#motion)
* [Plugin Management](#plugin-management)
* [Quickfix](#quickfix)
* [Statusline](#statusline)
* [UI](#ui)
* [Vim Internal](#vim-internal)
* [Vimrc](#vimrc)

***

## AI Assistants

|                                                                                                                                  |                                                                                                |      |
| -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---- |
| [DanBradbury/copilot-chat.vim](https://github.com/DanBradbury/copilot-chat.vim) ⭐ 134 \| 🐛 25 \| 🌐 Vim Script \| 📅 2026-01-17 | Copilot Chat for Vim                                                                           | ⭐134 |
| [greeschenko/vim9-ollama](https://github.com/greeschenko/vim9-ollama) ⭐ 14 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-03-14             | Local driven AI assistent plugin written in the cutting-edge Vim9 script and powered by ollama | ⭐14  |

## Color Scheme

|                                                                                                                               |                                                                                          |    |
| ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | -- |
| [micdzu/aalto.vim](https://codeberg.org/micdzu/aalto.vim)                                                                     | A Vim (v9) colorscheme where structure becomes visible — and everything else fades away. | ⭐1 |
| [mao-yining/vim-catppuccin](https://codeberg.org/mao-yining/vim-catppuccin)                                                   | 🧋 Soothing pastel theme for Vim                                                         | ⭐1 |
| [zhixiao-zhang/vim-light-pink](https://github.com/zhixiao-zhang/vim-light-pink) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-02-11 | A vim color scheme reproduction of a vscode theme.                                       | ⭐0 |
| [kratuvid/vim9-gruvbox](https://github.com/kratuvid/vim9-gruvbox) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-03-07               | A vim9script port of Gruvbox                                                             | ⭐3 |

## Command Execution

|                                                                                                                          |                                                                                                                                                                                                                                                   |     |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| [hahdookin/miniterm.vim](https://github.com/hahdookin/miniterm.vim) ⭐ 26 \| 🐛 2 \| 🌐 Vim Script \| 📅 2024-03-24       | Simple Vim9 toggle-terminal manager                                                                                                                                                                                                               | ⭐26 |
| [habamax/vim-shout](https://github.com/habamax/vim-shout) ⭐ 31 \| 🐛 4 \| 🌐 Vim Script \| 📅 2025-09-12                 | Run and Capture Shell Command Output in Vim                                                                                                                                                                                                       | ⭐31 |
| [ShayHill/vim9-scratchterm](https://github.com/ShayHill/vim9-scratchterm) ⭐ 12 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-08-26 | Define a command, ScratchTerm, that creates a new terminal buffer and marks it as a scratch buffer. This allows us to kill all scratch terminals in the current view with a single function.                                                      | ⭐12 |
| [sevehub/vim9lua](https://github.com/sevehub/vim9lua) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-08-18                      | This Vim9Script plugin allows users to execute the contents of the current buffer as a Lua script using Windows PowerShell. It provides a way to test and run Lua code directly from Vim, enhancing the development workflow for Lua programmers. | ⭐0  |

## Completion

|                                                                                                                           |                                                                                          |      |
| ------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---- |
| [jessepav/vim-camelcomplete](https://github.com/jessepav/vim-camelcomplete) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-05-20 | Vim 9 plugin to complete CamelCase, snake\_case and dash-words identifier abbreviations. | ⭐4   |
| [mityu/vim-wispath](https://github.com/mityu/vim-wispath) ⭐ 6 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-12-24                   | A path completion script written in Vim9 script.                                         | ⭐6   |
| [girishji/vimcomplete](https://github.com/girishji/vimcomplete) ⭐ 182 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-10-05           | Async autocompletion for Vim.                                                            | ⭐182 |
| [girishji/vimsuggest](https://github.com/girishji/vimsuggest) ⭐ 53 \| 🐛 1 \| 🌐 Vim Script \| 📅 2025-10-05              | Auto-completion for Vim's command-line.                                                  | ⭐53  |

## Editing

|                                                                                                                                |                                                                        |     |
| ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | --- |
| [Eliot00/auto-pairs](https://github.com/Eliot00/auto-pairs) ⭐ 22 \| 🐛 0 \| 🌐 Vim Script \| 📅 2022-09-15                     | Vim9 auto pairs plugin                                                 | ⭐22 |
| [nda-cunh/SupraComment](https://github.com/nda-cunh/SupraComment) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-04-12                | Vim9 commenting plugin inspired by VS Code’s Ctrl + / behavior.        | ⭐1  |
| [ubaldot/vim-highlight-yanked](https://github.com/ubaldot/vim-highlight-yanked) ⭐ 14 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-08-25 | Highlight yanked text for Vim9 in less than 100 lines of code.         | ⭐14 |
| [ubaldot/vim-op-surround](https://github.com/ubaldot/vim-op-surround) ⭐ 6 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-31            | Vim9 surround!                                                         | ⭐6  |
| [ubaldot/vim-writegood](https://github.com/ubaldot/vim-writegood) ⭐ 2 \| 🐛 1 \| 🌐 Vim Script \| 📅 2023-05-31                | Check your English prose in Vim.                                       | ⭐2  |
| [nda-cunh/vim9-autopairs](https://github.com/nda-cunh/vim9-autopairs) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-05-05            | Vim9 auto pairs plugin                                                 | ⭐2  |
| [Coacher/vim9-buckler](https://github.com/Coacher/vim9-buckler) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-15                  | Vim9 plugin that maintains a consistent yank history through registers | ⭐4  |
| [Coacher/vim9-cutlass](https://github.com/Coacher/vim9-cutlass) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-01-12                  | Vim9 plugin that adds a 'cut' operation separate from 'delete'         | ⭐3  |
| [ShayHill/vim9-socialfmt](https://github.com/ShayHill/vim9-socialfmt) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-04-14            | Emulate formatted text for LinkedIn, X, Facebook, and more.            | ⭐1  |

## File Management

|                                                                                                                     |                                                       |     |
| ------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | --- |
| [jarkko/oulu.vim](https://codeberg.org/jarkko/oulu.vim)                                                             | *No description provided.*                            | ⭐1  |
| [ycm/poplar.vim](https://github.com/ycm/poplar.vim) ⭐ 23 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-05-09                  | Popup filetree and pinned files for vim9              | ⭐23 |
| [nda-cunh/SupraTree](https://github.com/nda-cunh/SupraTree) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-06           | A tree for vim                                        | ⭐1  |
| [nda-cunh/SupraWater](https://github.com/nda-cunh/SupraWater) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-20         | 🌊 Vim9script plugin File-Manager like nvim-oil       | ⭐4  |
| [habamax/vim-dir](https://github.com/habamax/vim-dir) ⭐ 74 \| 🐛 4 \| 🌐 Vim Script \| 📅 2026-08-13                | Vim file manager                                      | ⭐74 |
| [saccarosium/vim-netrw-salad](https://github.com/saccarosium/vim-netrw-salad) ⚠️ Archived                           | A delicious salad to go with your beloved netrw.      | ⭐2  |
| [ubaldot/vim-open-recent](https://github.com/ubaldot/vim-open-recent) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-03-10 | Open recent files from a popup menu. Written in Vim9. | ⭐3  |

## Fuzzy Finding

|                                                                                                                       |                                                                                     |      |
| --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ---- |
| [vim-fuzzbox/fuzzbox.vim](https://github.com/vim-fuzzbox/fuzzbox.vim) ⭐ 162 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-22 | Modern fuzzy finder for Vim with minimal dependencies                               | ⭐162 |
| [hahdookin/minifuzzy.vim](https://github.com/hahdookin/minifuzzy.vim) ⭐ 12 \| 🐛 1 \| 🌐 Vim Script \| 📅 2024-12-09  | Simple Vim9 fuzzy finder wrapper utilizing Vim9's built-in fuzzy finding capability | ⭐12  |
| [girishji/scope.vim](https://github.com/girishji/scope.vim) ⭐ 90 \| 🐛 3 \| 🌐 Vim Script \| 📅 2026-05-04            | Minimal, fast, and extensible fuzzy finder.                                         | ⭐90  |
| [bfrg/vim-fzy](https://github.com/bfrg/vim-fzy) ⭐ 16 \| 🐛 0 \| 🌐 Vim Script \| 📅 2023-12-24                        | Run fzy asynchronously in a Vim (popup) terminal-window                             | ⭐16  |
| [ubaldot/vim-poptools](https://github.com/ubaldot/vim-poptools) ⭐ 19 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-20        | Exploit popups as much as you can!                                                  | ⭐19  |

## Games

|                                                                                                                   |                                                  |     |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | --- |
| [yegappan/battleship](https://github.com/yegappan/battleship) ⭐ 12 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-02-23      | Battleship game for Vim                          | ⭐12 |
| [nda-cunh/Crumble.vim](https://github.com/nda-cunh/Crumble.vim) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-12     | Crumble the buffer you're looking at.            | ⭐0  |
| [yegappan/game2048](https://github.com/yegappan/game2048) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23           | Game 2048 implemented using Vim9script           | ⭐2  |
| [yegappan/minesweeper](https://github.com/yegappan/minesweeper) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23     | Minesweeper game using Vim9script                | ⭐1  |
| [yegappan/nonogram](https://github.com/yegappan/nonogram) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23           | Nonogram game written in Vim9script              | ⭐3  |
| [yegappan/number-puzzle](https://github.com/yegappan/number-puzzle) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23 | Sliding number puzzle game written in Vim9script | ⭐3  |
| [yegappan/snake](https://github.com/yegappan/snake) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23                 | Snake Game in Vim9script                         | ⭐3  |
| [nda-cunh/SupraPacman](https://github.com/nda-cunh/SupraPacman) ⭐ 11 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-18    | vim9.1 plugin for playing to pacman in vim       | ⭐11 |
| [nda-cunh/SupraSnake](https://github.com/nda-cunh/SupraSnake) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-16       | a vim9script plugin for Add a SnakeGame !        | ⭐3  |
| [yegappan/tetris](https://github.com/yegappan/tetris) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23               | Tetris game in Vim9script                        | ⭐2  |
| [yegappan/tic-tac-toe](https://github.com/yegappan/tic-tac-toe) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-23     | Tic-Tac-Toe game in Vim9script                   | ⭐3  |

## Guides

|                                                                                                                                                      |                                                                                                                                                                         |     |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| [ShayHill/article\_install\_vim\_in\_windows](https://github.com/ShayHill/article_install_vim_in_windows) ⭐ 19 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-13 | This guide will start from a stock Windows 11 install and take you all the way to a Python development environment with completion, snippets, LSPs, debugging, AI, etc. | ⭐19 |
| [yegappan/design-patterns](https://github.com/yegappan/design-patterns) ⭐ 9 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-18                                | Design patterns in Vim9script                                                                                                                                           | ⭐9  |

## Integrations

|                                                                                                                                   |                                                                            |      |
| --------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ---- |
| [noscript/bazel.vim](https://github.com/noscript/bazel.vim) ⭐ 5 \| 🐛 0 \| 🌐 Vim Script \| 📅 2023-08-19                         | Google Bazel integration for Vim                                           | ⭐5   |
| [gh-tui-tools/gh-review.vim](https://github.com/gh-tui-tools/gh-review.vim) ⭐ 11 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-01        | 🧐 Review GitHub PRs in Vim 9.0+                                           | ⭐11  |
| [DanBradbury/github-actions.vim](https://github.com/DanBradbury/github-actions.vim) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-12-06 | Interact with GitHub Actions in vim                                        | ⭐2   |
| [mao-yining/gv.vim](https://github.com/mao-yining/gv.vim) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-23                           | A git commit browser in Vim. Rewrite in vim9script. Require vim-fugitive   | ⭐1   |
| [gcanat/texpresso.vim9](https://github.com/gcanat/texpresso.vim9) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-11-14                   | vim mode for texpresso                                                     | ⭐2   |
| [bfrg/vim-cmake-help](https://github.com/bfrg/vim-cmake-help) ⭐ 8 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-07-13                       | View CMake Documentation inside Vim                                        | ⭐8   |
| [ubaldot/vim-conda-activate](https://github.com/ubaldot/vim-conda-activate) ⭐ 18 \| 🐛 3 \| 🌐 Vim Script \| 📅 2025-02-06        | Activate Conda environments in Vim.                                        | ⭐18  |
| [habamax/vim-curl](https://github.com/habamax/vim-curl) ⭐ 6 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-07-03                             | Simple curl wrapper for vim to work with REST API                          | ⭐6   |
| [ubaldot/vim-git-box](https://github.com/ubaldot/vim-git-box) ⭐ 2 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-07-23                       | A tiny Vim plugin for everyday git operations, inspired by lazygit         | ⭐2   |
| [habamax/vim-ii](https://github.com/habamax/vim-ii) ⭐ 13 \| 🐛 4 \| 🌐 Vim Script \| 📅 2025-06-17                                | IRC with suckless Irc it (ii) and vim                                      | ⭐13  |
| [bfrg/vim-jqplay](https://github.com/bfrg/vim-jqplay) ⭐ 124 \| 🐛 2 \| 🌐 Vim Script \| 📅 2024-03-05                             | Run jq interactively in Vim                                                | ⭐124 |
| [ubaldot/vim-manim](https://github.com/ubaldot/vim-manim) ⭐ 6 \| 🐛 2 \| 🌐 Vim Script \| 📅 2025-08-25                           | Render your manim-ations from Vim.                                         | ⭐6   |
| [ubaldot/vim-microdebugger](https://github.com/ubaldot/vim-microdebugger) ⭐ 6 \| 🐛 3 \| 🌐 Vim Script \| 📅 2025-08-25           | A tiny plugin on top of Termdebug for remote debugging (docker, MCUs, etc) | ⭐6   |
| [ubaldot/vim-replica](https://github.com/ubaldot/vim-replica) ⭐ 32 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-08-20                      | The ultimate REPL!                                                         | ⭐32  |
| [mao-yining/vim-signify](https://codeberg.org/mao-yining/vim-signify)                                                             | ➕ Show a diff using Vim its sign column.                                   | ⭐1   |
| [wolandark/vimdict](https://github.com/wolandark/vimdict) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-06-23                           | A Simple Wrapper Over The Dict CLI Utility For Vim9                        | ⭐4   |

## Language Server Protocol

|                                                                                                                            |                                                                    |      |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ---- |
| [DanielViberg/lsp](https://github.com/DanielViberg/lsp) ⭐ 2 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-08-24                      | A lightweight, pure vim9script lsp client                          | ⭐2   |
| [yegappan/lsp](https://github.com/yegappan/lsp/tree/main) ⭐ 766 \| 🐛 115 \| 🌐 Vim Script \| 📅 2026-08-17                | Language Server Protocol (LSP) plugin for Vim9                     | ⭐764 |
| [h-east/lsp.vim](https://github.com/h-east/lsp.vim) ⭐ 6 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-08-27                          | A Language Server Protocol client for Vim, written in Vim9 script. | ⭐3   |
| [creativenull/vim-lspclient](https://github.com/creativenull/vim-lspclient) ⭐ 18 \| 🐛 0 \| 🌐 Vim Script \| 📅 2022-09-01 | A highly experimental lsp client for vim. Written in vim9script.   | ⭐18  |
| [saccarosium/yegappan-lsp-settings](https://github.com/saccarosium/yegappan-lsp-settings) ⚠️ Archived                      | Quickstart configs for yeggapan lsp client                         | ⭐4   |

## Libraries

|                                                                                                                          |                                                               |     |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------- | --- |
| [pit-ray/vim-autograd](https://github.com/pit-ray/vim-autograd/tree/vim9) ⭐ 29 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-02-23 | Automatic differentiation library written in pure Vim script. | ⭐29 |
| [lifepillar/vim-colortemplate](https://codeberg.org/lifepillar/vim-colortemplate/src/branch/v3)                          | The Toolkit for Vim Color Scheme Designers!                   | ⭐7  |
| [lifepillar/vim-devel](https://codeberg.org/lifepillar/vim-devel)                                                        | The workbench for modern Vim development                      | ⭐2  |

## Markdown

|                                                                                                                              |                                                                 |     |
| ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- | --- |
| [JosefAlbers/thumb](https://github.com/JosefAlbers/thumb) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-24                      | Popup images and render LaTeX directly in Vim                   | ⭐0  |
| [ubaldot/vim-markdown-extras](https://github.com/ubaldot/vim-markdown-extras) ⭐ 13 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-07-31 | Modern note taking plugin with markdown focus                   | ⭐13 |
| [greeschenko/vimsidian](https://github.com/greeschenko/vimsidian) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-06-20              | Minimalistic Obsidian-like note system inside Vim (Vim9script). | ⭐2  |

## Miscellaneous

|                                                                                                                              |                                                                                                                                                                  |     |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| [nda-cunh/PropColor](https://github.com/nda-cunh/PropColor) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-06-07                    | vim9script plugin to draw colors in your editor                                                                                                                  | ⭐4  |
| [nda-cunh/SupraIcons](https://github.com/nda-cunh/SupraIcons) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-05-13                  | Icons and Palette plugin vim9                                                                                                                                    | ⭐2  |
| [jessepav/vim-boxdraw](https://github.com/jessepav/vim-boxdraw) ⭐ 8 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-05-20                | Vim 9 plugin to draw boxes, tables, and lines                                                                                                                    | ⭐8  |
| [ubaldot/vim-calendar](https://github.com/ubaldot/vim-calendar) ⭐ 2 \| 🐛 2 \| 🌐 Vim Script \| 📅 2026-08-13                | Calendar in Vim9                                                                                                                                                 | ⭐2  |
| [mao-yining/vim-competitest](https://codeberg.org/mao-yining/vim-competitest)                                                | CompetiTest.vim is a Vim plugin for Competitive Programming: it can manage and check testcases, download problems and contests from online judges and much more. | ⭐1  |
| [wolandark/vim-ez-emoji](https://github.com/wolandark/vim-ez-emoji) ⭐ 12 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-02-15           | An easy emoji plugin for vim written in vim9script                                                                                                               | ⭐12 |
| [ubaldot/vim-helpme](https://github.com/ubaldot/vim-helpme) ⭐ 11 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-07-28                   | Can't you remember stuff? Try this!                                                                                                                              | ⭐11 |
| [ubaldot/vim-outline](https://github.com/ubaldot/vim-outline) ⭐ 23 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-07-31                 | A simple outline sketcher for different filetypes.                                                                                                               | ⭐23 |
| [mags/vim-srt](https://codeberg.org/mags/vim-srt)                                                                            | Vim9 subtitle filetype plugin                                                                                                                                    | ⭐0  |
| [ubaldot/vim9-conversion-aid](https://github.com/ubaldot/vim9-conversion-aid) ⭐ 16 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-21 | A little help for upgrading your scripts to vim9 language.                                                                                                       | ⭐16 |
| [lacygoill/vim9asm](https://github.com/lacygoill/vim9asm) ⭐ 24 \| 🐛 3 \| 🌐 Vim Script \| 📅 2025-07-25                     | *No description provided.*                                                                                                                                       | ⭐24 |
| [sevehub/vim9psgrep](https://github.com/sevehub/vim9psgrep) ⭐ 1 \| 🐛 1 \| 🌐 PowerShell \| 📅 2025-02-05                    | vim9psgrep is a Vim9script plugin that integrates the power of ripgrep with Vim, utilizing PowerShell scripts and Visual Basic popups                            | ⭐1  |

## Motion

|                                                                                                                     |                                                  |      |
| ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ---- |
| [girishji/easyjump.vim](https://github.com/girishji/easyjump.vim) ⭐ 20 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-06-06    | The Vim motion you've always wanted.             | ⭐20  |
| [girishji/fFtT.vim](https://github.com/girishji/fFtT.vim) ⭐ 10 \| 🐛 1 \| 🌐 Vim Script \| 📅 2024-06-06            | More accurate f, F, t, T navigation in Vim.      | ⭐10  |
| [monkoose/vim9-stargate](https://github.com/monkoose/vim9-stargate) ⭐ 123 \| 🐛 1 \| 🌐 Vim Script \| 📅 2024-01-17 | modern alternative to easymotion written in vim9 | ⭐123 |

## Plugin Management

|                                                                                                                |                                                                                               |     |
| -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --- |
| [bennyyip/plugpac.vim](https://github.com/bennyyip/plugpac.vim) ⭐ 63 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-09-07 | Plugpac is a plugin manger written in Vim9 based on minpac, provides vim-plug-like experience | ⭐63 |

## Quickfix

|                                                                                                                      |                                                                                                       |     |
| -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | --- |
| [doruk/tsc-watcher-vim](https://codeberg.org/doruk/tsc-watcher-vim)                                                  | Quickfix list generation based on tsc output, uglier version of custom `set makeprg=...` for TS files | ⭐0  |
| [bfrg/vim-qf-diagnostics](https://github.com/bfrg/vim-qf-diagnostics) ⭐ 30 \| 🐛 1 \| 🌐 Vim Script \| 📅 2024-07-26 | Highlight quickfix errors, and display error messages as virtual text or in a popup window            | ⭐30 |
| [bfrg/vim-qf-history](https://github.com/bfrg/vim-qf-history) ⭐ 13 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-02-02         | Navigate Vim's quickfix and location-list history using a popup menu                                  | ⭐13 |
| [bfrg/vim-qf-preview](https://github.com/bfrg/vim-qf-preview) ⭐ 55 \| 🐛 1 \| 🌐 Vim Script \| 📅 2024-02-02         | Preview the quickfix item under the cursor in a popup window                                          | ⭐55 |

## Statusline

|                                                                                                                           |                                                                                                    |        |
| ------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------ |
| [senioria/lines9](https://github.com/senioria/lines9) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-01-16                       | A statusline/tabline plugin written in vim9script                                                  | ⭐2     |
| [Bakudankun/qline.vim](https://github.com/Bakudankun/qline.vim) ⭐ 44 \| 🐛 1 \| 🌐 Vim Script \| 📅 2025-10-12            | The quick, fully-customizable status line plugin written in cutting-edge Vim9 script.              | ⭐44    |
| [vim-airline/vim-airline](https://github.com/vim-airline/vim-airline) ⭐ 17,959 \| 🐛 38 \| 🌐 Vim Script \| 📅 2026-07-25 | lean & mean status/tabline for vim that's light as air                                             | ⭐17959 |
| [kennypete/vim-tene](https://github.com/kennypete/vim-tene) ⭐ 17 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-01-07                | Vim 9 - teRNARY STATUSLIne                                                                         | ⭐17    |
| [ShayHill/vim9-limelight](https://github.com/ShayHill/vim9-limelight) ⭐ 10 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-01      | Shade unfocused windows. Give a bright statusline color for active windows *when splits are open*. | ⭐10    |

## UI

|                                                                                                                               |                                                                                        |     |
| ----------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | --- |
| [noscript/elevator.vim](https://github.com/noscript/elevator.vim) ⭐ 12 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-12-21              | Scrollbar for VIM                                                                      | ⭐12 |
| [nda-cunh/indent\_rainbow\_vim](https://github.com/nda-cunh/indent_rainbow_vim) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-08-28 | vim9 plugin for indent\_rainbow from supravim                                          | ⭐3  |
| [Bakudankun/minimap.vim](https://github.com/Bakudankun/minimap.vim) ⭐ 5 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-19             | minimap plugin written in pure Vim9 script.                                            | ⭐5  |
| [Bakudankun/partycursor.vim](https://github.com/Bakudankun/partycursor.vim) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-04-17     | PARTY OR IDE                                                                           | ⭐1  |
| [nda-cunh/smear\_cursor-vim](https://github.com/nda-cunh/smear_cursor-vim) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-01      | Fire your cursor !                                                                     | ⭐0  |
| [Bakudankun/sqroller.vim](https://github.com/Bakudankun/sqroller.vim) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2024-10-18           | Scrollbar plugin for those who don't need foldcolumn.                                  | ⭐0  |
| [noscript/taberian.vim](https://github.com/noscript/taberian.vim) ⭐ 19 \| 🐛 1 \| 🌐 Vim Script \| 📅 2023-08-08              | Clickable tabs per VIM window                                                          | ⭐19 |
| [mao-yining/undotree.vim](https://github.com/mao-yining/undotree.vim) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-18           | The undo history visualizer for VIM                                                    | ⭐4  |
| [utubo/vim-anypanel](https://github.com/utubo/vim-anypanel) ⭐ 5 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-03-02                     | 📑This is a plugin that helps you customize the tab panel.                             | ⭐5  |
| [ubaldot/vim-extended-view](https://github.com/ubaldot/vim-extended-view) ⭐ 6 \| 🐛 1 \| 🌐 Vim Script \| 📅 2025-08-25       | A window is too small for your long buffer? Then, try this!                            | ⭐6  |
| [kennypete/vim-popped](https://github.com/kennypete/vim-popped) ⭐ 10 \| 🐛 1 \| 🌐 Vim Script \| 📅 2023-10-29                | A plugin for Vim providing commands that use Vim’s builtin popup window functionality. | ⭐10 |
| [mattn/vim-smear-cursor](https://github.com/mattn/vim-smear-cursor) ⭐ 6 \| 🐛 1 \| 🌐 Vim Script \| 📅 2026-03-15             | *No description provided.*                                                             | ⭐6  |
| [kennypete/vim9-winswap](https://github.com/kennypete/vim9-winswap) ⭐ 3 \| 🐛 0 \| 🌐 Vim Script \| 📅 2025-07-20             | A Vim9 script plugin enabling easy swapping and putting of windows                     | ⭐3  |

## Vim Internal

|                                                                                                                                                               |                       |         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ------- |
| [vim/.../pack/.../cfilter](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/cfilter) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26       | :h package-cfilter    | **N/A** |
| [vim/.../pack/.../comment](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/comment/) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26      | :h package-comment    | **N/A** |
| [vim/.../pack/.../helpcurwin](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/helpcurwin) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26 | :h package-helpcurwin | **N/A** |
| [vim/.../pack/.../helptoc](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/helptoc) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26       | :h package-helptoc    | **N/A** |
| [vim/.../pack/.../hlyank](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/hlyank/) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26        | :h package-hlyank     | **N/A** |
| [vim/.../pack/.../osc52](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/osc52) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26           | :h package-osc52      | **N/A** |
| [vim/.../pack/.../termdebug](https://github.com/vim/vim/tree/master/runtime/pack/dist/opt/termdebug) ⭐ 40,806 \| 🐛 1,625 \| 🌐 Vim Script \| 📅 2026-08-26   | :h package-termdebug  | **N/A** |

## Vimrc

|                                                                                                                      |                                                       |     |
| -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | --- |
| [habamax/.vim](https://github.com/habamax/.vim) ⭐ 85 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-26                       | Personal .vim                                         | ⭐85 |
| [kennypete/.vimrc](https://github.com/kennypete/.vimrc) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-29                | My .vimrc                                             | ⭐4  |
| [lacygoill/config](https://github.com/lacygoill/config/tree/main/.vim) ⭐ 0 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-23 | *No description provided.*                            | ⭐0  |
| [bennyyip/dot-vim](https://github.com/bennyyip/dot-vim) ⭐ 9 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-28                | *No description provided.*                            | ⭐9  |
| [mao-yining/dotfile\_vim](https://codeberg.org/mao-yining/dotfile_vim)                                               | *No description provided.*                            | ⭐1  |
| [64-bitman/vim-config](https://github.com/64-bitman/vim-config) ⭐ 2 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-07-23        | *No description provided.*                            | ⭐2  |
| [ShayHill/vimfiles](https://github.com/ShayHill/vimfiles) ⭐ 1 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-03              | my personal vimfiles for mostly Python dev on Windows | ⭐1  |
| [beamiter/vimrc](https://github.com/beamiter/vimrc/) ⭐ 4 \| 🐛 0 \| 🌐 Vim Script \| 📅 2026-08-21                   | vimrc                                                 | ⭐4  |

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
