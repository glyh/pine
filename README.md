# [VAPORWARE] pine
The "Pine Is Not Emcas" editor

# Goals
- A GUI text editor with the following focus
  - Coding
  - Journal Writing
  - Documentation Writing
  - In a word, I want to implement an emacs with org-mode, I choose to make org-mode built-in because  
    same problem have been solving again & again with different solution.
- Autocomplete, Syntax Highlight, Extension Management
- *EXTREMELY* easy to customize
    - In any language you love.
    - Modify behavior in runtime.
    - Modify editor's source in runtime.
- Selection based editing modal similar to Kakoune/Helix.
- Cross platform
  - Should be able to run in
    - Windows
    - Linux
    - MacOS (x86\_64 and ARM)
    - WASM
- Responsive!!!!
  - One of the reason I don't want to use Emacs is that it feels too slow.
- Modern Interface
  - One of the reason people don't like emacs is because the language along with the interface,
  since pine is a complete rewrite, it should be possible to put people in a better situation.

# Why not 
- vim/neovim
  - It's a TUI software, many features simply isn't possible
- emacs
  - Afaik, there's no WISIWYG document editing, but I planned to make it in Pine
  - Also emacs is not responsive enough.
- other note taking platform
  - well if you're not programmer I would argue that those are better for you, but those softwares are 
  not as customizable as pine and they are not designed to integrate well with codes.

# Non Goals
- Start up time
  - pine is expected to run as a services, having said that, it should be able to start with in 0.5S

# Nice to have
- Replace a lot of softwares
  - replace [bat](https://github.com/sharkdp/bat)
  - provide something similar to [firenvim](https://github.com/glacambre/firenvim)

# Things come up to mind
- Integration of window spliting with host.
  - Planned
    - I3WM & Sway
    - Hyprland
