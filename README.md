# Laptop configurations

## User Installed macOS Apps
- Alfred 4
- Brave
- CheatSheet
- Docker
- Flameshot
- GIPHY CAPTURE
- Hazel
- Obisdian
- Postman
- Rectangle
- Visual Studio Code
- Zotero

## macOS System Preferences
```shell
➜ defaults write NSGlobalDomain KeyRepeat -int 0
➜ defaults write NSGlobalDomain InitialKeyRepeat -int 15
```
## Custom Fonts
- https://github.com/powerline/fonts.git

## Homebrew Packages
```shell
➜ brew leaves --installed-on-request | xargs -n1 brew desc
act: Run your GitHub Actions locally 🚀
antigen: Plugin manager for zsh, inspired by oh-my-zsh and vundle
asdf: Extendable version manager with support for Ruby, Node.js, Erlang & more
awscli: Official Amazon AWS command-line interface
bison: Parser generator
chruby: Ruby environment tool
direnv: Load/unload environment variables based on $PWD
fd: Simple, fast and user-friendly alternative to find
fzf: Command-line fuzzy finder written in Go
gcc: GNU compiler collection
go: Open source programming language to build simple/reliable/efficient software
helm: Kubernetes package manager
htop: Improved top (interactive process viewer)
jq: Lightweight and flexible command-line JSON processor
kube-ps1: Kubernetes prompt info for bash and zsh
pango: Framework for layout and rendering of i18n text
php: General-purpose scripting language
pre-commit: Framework for managing multi-language pre-commit hooks
pyenv-virtualenvwrapper: Alternative to pyenv for managing virtualenvs
ruby-install: Install Ruby, JRuby, Rubinius, TruffleRuby, or mruby
spaceship: Zsh prompt for Astronauts
starship: Cross-shell prompt for astronauts
terraform: Tool to build, change, and version infrastructure
terraform-docs: Tool to generate documentation from Terraform modules
terrascan: Detect compliance and security violations across Infrastructure as Code
tfenv: Terraform version manager inspired by rbenv
tflint: Linter for Terraform files
tfsec: Static analysis security scanner for your terraform code
tree: Display directories as trees (with optional color/HTML output)
eksctl: The official CLI for Amazon EKS
xclip: Access X11 clipboards from the command-line
zsh-autosuggestions: Fish-like fast/unobtrusive autosuggestions for zsh
zsh-syntax-highlighting: Fish shell like syntax highlighting for zsh

➜ brew leaves | xargs -n1 brew desc
act: Run your GitHub Actions locally 🚀
antigen: Plugin manager for zsh, inspired by oh-my-zsh and vundle
asdf: Extendable version manager with support for Ruby, Node.js, Erlang & more
awscli: Official Amazon AWS command-line interface
bison: Parser generator
chruby: Ruby environment tool
direnv: Load/unload environment variables based on $PWD
fd: Simple, fast and user-friendly alternative to find
fzf: Command-line fuzzy finder written in Go
gcc: GNU compiler collection
go: Open source programming language to build simple/reliable/efficient software
helm: Kubernetes package manager
htop: Improved top (interactive process viewer)
jq: Lightweight and flexible command-line JSON processor
kube-ps1: Kubernetes prompt info for bash and zsh
pango: Framework for layout and rendering of i18n text
php: General-purpose scripting language
pre-commit: Framework for managing multi-language pre-commit hooks
pyenv-virtualenvwrapper: Alternative to pyenv for managing virtualenvs
ruby-install: Install Ruby, JRuby, Rubinius, TruffleRuby, or mruby
spaceship: Zsh prompt for Astronauts
starship: Cross-shell prompt for astronauts
terraform: Tool to build, change, and version infrastructure
terraform-docs: Tool to generate documentation from Terraform modules
terrascan: Detect compliance and security violations across Infrastructure as Code
tfenv: Terraform version manager inspired by rbenv
tflint: Linter for Terraform files
tfsec: Static analysis security scanner for your terraform code
tree: Display directories as trees (with optional color/HTML output)
eksctl: The official CLI for Amazon EKS
xclip: Access X11 clipboards from the command-line
zsh-autosuggestions: Fish-like fast/unobtrusive autosuggestions for zsh
zsh-syntax-highlighting: Fish shell like syntax highlighting for zsh

➜ brew list --cask
caffeine
flameshot
```

## Obsidian (Settings, Extensions, Keybindings, Themes)

## Visual Studio Code (Settings, Extensions, Keybindings, Themes)
### Extensions
```shell
➜ code --list-extensions | xargs -L 1 echo code --install-extension

code --install-extension alefragnani.Bookmarks
code --install-extension bierner.markdown-emoji
code --install-extension eamodio.gitlens
code --install-extension enkia.tokyo-night
code --install-extension esbenp.prettier-vscode
code --install-extension frhtylcn.pythonsnippets
code --install-extension GitHub.copilot
code --install-extension golang.go
code --install-extension hashicorp.terraform
code --install-extension lextudio.restructuredtext
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-kubernetes-tools.vscode-kubernetes-tools
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension ms-toolsai.jupyter
code --install-extension ms-toolsai.jupyter-keymap
code --install-extension ms-toolsai.jupyter-renderers
code --install-extension ms-vscode-remote.remote-containers
code --install-extension ms-vscode-remote.remote-ssh
code --install-extension ms-vscode-remote.remote-ssh-edit
code --install-extension ms-vscode-remote.remote-wsl
code --install-extension ms-vscode-remote.vscode-remote-extensionpack
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension ms-vsliveshare.vsliveshare-audio
code --install-extension ms-vsliveshare.vsliveshare-pack
code --install-extension njpwerner.autodocstring
code --install-extension RandomFractalsInc.vscode-data-preview
code --install-extension redhat.vscode-yaml
code --install-extension ritwickdey.LiveServer
code --install-extension sdras.night-owl
code --install-extension Shan.code-settings-sync
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension t-nano.markdown-to-confluence-vscode
code --install-extension tkcandrade.code-annotation
code --install-extension trond-snekvik.simple-rst
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension yzhang.markdown-all-in-one
```
### Keybindings
```shell
Application Support/Code/User
➜ cat keybindings.json
```
```json
[
  {
    "key": "alt+cmd+`",
    "command": "workbench.action.toggleMaximizedPanel"
  },
  {
    "key": "shift+cmd+0",
    "command": "workbench.files.action.collapseExplorerFolders"
  },
  {
    "key": "shift+cmd+e",
    "command": "workbench.files.action.showActiveFileInExplorer"
  },
  {
    "key": "alt+cmd+b",
    "command": "workbench.action.tasks.build"
  },
  {
    "key": "shift+cmd+b",
    "command": "-workbench.action.tasks.build"
  },
  {
    "key": "shift+cmd+b",
    "command": "workbench.action.toggleSidebarVisibility"
  },
  {
    "key": "cmd+b",
    "command": "-workbench.action.toggleSidebarVisibility"
  }
]
```

### Settings
```shell
Application Support/Code/User using ☁️ saml
➜ cat settings.json
```
```json
{
  "workbench.colorTheme": "Solarized Light",
  "terminal.external.osxExec": "iTerm.app",
  "terminal.integrated.defaultProfile.osx": "zsh",
  "terminal.integrated.fontFamily": "'Fira Mono for Powerline'",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontSize": 13,
  "editor.fontSize": 13,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "files.autoSave": "onFocusChange",
  "gitlens.codeLens.scopes": [],
  "gitlens.codeLens.recentChange.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "security.workspace.trust.untrustedFiles": "open",
  "[terraform]": {
    "editor.defaultFormatter": "hashicorp.terraform",
    "editor.formatOnSave": true,
    "editor.formatOnSaveMode": "file"
  },
  "[terraform-vars]": {
    "editor.defaultFormatter": "hashicorp.terraform",
    "editor.formatOnSave": true,
    "editor.formatOnSaveMode": "file"
  },
  "terraform-ls.experimentalFeatures": {
    "validateOnSave": true
  },
  "python.formatting.provider": "black",
  "editor.fontFamily": "'Fira Mono for Powerline', 'Fira Mono', Menlo, Monaco, 'Courier New', monospace",
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,
  "sync.gist": "40950d060aa704fd0a151dc5c9ab8761",
  "sync.autoUpload": true,
  "editor.inlineSuggest.enabled": true,
  "sync.quietSync": true,
  "github.copilot.enable": {
    "*": true,
    "yaml": true,
    "plaintext": true,
    "markdown": true
  },
  "editor.renderWhitespace": "none",
  "workbench.startupEditor": "none",
  "[python]": {
    "editor.defaultFormatter": "ms-python.python"
  },
  "editor.rulers": [80, 120],
  "vs-kubernetes": {
    "vs-kubernetes.knownKubeconfigs": [
      "/Users/drewm/.kube/custom-contexts/mcp/config",
      "/Users/drewm/.kube/custom-contexts/jpl-aws/config",
      "~/.kube/config"
    ],
    "vs-kubernetes.kubeconfig": "/Users/drewm/.kube/custom-contexts/mcp/config"
  },
  "vscode-kubernetes.kubectl-path.linux": "undefined",
  "vscode-kubernetes.kubectl-path.mac": "/usr/local/bin/kubectl",
  "vscode-kubernetes.kubectl-path": "/usr/local/bin/kubectl",
  "[go]": {
    "editor.defaultFormatter": "golang.go"
  },
  "window.zoomLevel": -1
}
```

## Rectangle Preferences
```json
{
  "bundleId" : "com.knollsoft.Rectangle",
  "defaults" : {
    "allowAnyShortcut" : {
      "bool" : false
    },
    "almostMaximizeHeight" : {
      "float" : 0
    },
    "almostMaximizeWidth" : {
      "float" : 0
    },
    "alternateDefaultShortcuts" : {
      "bool" : true
    },
    "altThirdCycle" : {
      "int" : 0
    },
    "applyGapsToMaximize" : {
      "int" : 0
    },
    "applyGapsToMaximizeHeight" : {
      "int" : 0
    },
    "attemptMatchOnNextPrevDisplay" : {
      "int" : 0
    },
    "autoMaximize" : {
      "int" : 0
    },
    "cascadeAllDeltaSize" : {
      "float" : 30
    },
    "centeredDirectionalMove" : {
      "int" : 0
    },
    "centerHalfCycles" : {
      "int" : 0
    },
    "cornerSnapAreaSize" : {
      "float" : 20
    },
    "curtainChangeSize" : {
      "int" : 0
    },
    "disabledApps" : {

    },
    "footprintAlpha" : {
      "float" : 0.30000001192092896
    },
    "footprintBorderWidth" : {
      "float" : 2
    },
    "footprintColor" : {

    },
    "footprintFade" : {
      "int" : 0
    },
    "fullIgnoreBundleIds" : {

    },
    "gapSize" : {
      "float" : 0
    },
    "hideMenubarIcon" : {
      "bool" : false
    },
    "ignoredSnapAreas" : {
      "int" : 0
    },
    "launchOnLogin" : {
      "bool" : true
    },
    "minimumWindowHeight" : {
      "float" : 0
    },
    "minimumWindowWidth" : {
      "float" : 0
    },
    "moveCursor" : {
      "int" : 0
    },
    "moveCursorAcrossDisplays" : {
      "int" : 0
    },
    "notifiedOfProblemApps" : {
      "bool" : false
    },
    "obtainWindowOnClick" : {
      "int" : 0
    },
    "relaunchOpensMenu" : {
      "bool" : false
    },
    "resizeOnDirectionalMove" : {
      "bool" : false
    },
    "screenEdgeGapBottom" : {
      "float" : 0
    },
    "screenEdgeGapLeft" : {
      "float" : 0
    },
    "screenEdgeGapRight" : {
      "float" : 0
    },
    "screenEdgeGapTop" : {
      "float" : 0
    },
    "shortEdgeSnapAreaSize" : {
      "float" : 145
    },
    "showAllActionsInMenu" : {
      "int" : 0
    },
    "sizeOffset" : {
      "float" : 0
    },
    "snapEdgeMarginBottom" : {
      "float" : 5
    },
    "snapEdgeMarginLeft" : {
      "float" : 5
    },
    "snapEdgeMarginRight" : {
      "float" : 5
    },
    "snapEdgeMarginTop" : {
      "float" : 5
    },
    "snapModifiers" : {
      "int" : 0
    },
    "specifiedHeight" : {
      "float" : 1050
    },
    "specifiedWidth" : {
      "float" : 1680
    },
    "subsequentExecutionMode" : {
      "int" : 1
    },
    "SUEnableAutomaticChecks" : {
      "bool" : false
    },
    "todo" : {
      "int" : 0
    },
    "todoApplication" : {

    },
    "todoMode" : {
      "bool" : false
    },
    "todoSidebarWidth" : {
      "float" : 400
    },
    "traverseSingleScreen" : {
      "int" : 0
    },
    "unsnapRestore" : {
      "int" : 0
    },
    "windowSnapping" : {
      "int" : 0
    }
  },
  "shortcuts" : {
    "bottomHalf" : {
      "keyCode" : 125,
      "modifierFlags" : 786432
    },
    "bottomLeft" : {
      "keyCode" : 38,
      "modifierFlags" : 786432
    },
    "bottomRight" : {
      "keyCode" : 40,
      "modifierFlags" : 786432
    },
    "center" : {
      "keyCode" : 8,
      "modifierFlags" : 786432
    },
    "centerThird" : {
      "keyCode" : 3,
      "modifierFlags" : 786432
    },
    "firstThird" : {
      "keyCode" : 2,
      "modifierFlags" : 786432
    },
    "firstTwoThirds" : {
      "keyCode" : 14,
      "modifierFlags" : 786432
    },
    "larger" : {
      "keyCode" : 24,
      "modifierFlags" : 786432
    },
    "lastThird" : {
      "keyCode" : 5,
      "modifierFlags" : 786432
    },
    "lastTwoThirds" : {
      "keyCode" : 17,
      "modifierFlags" : 786432
    },
    "leftHalf" : {
      "keyCode" : 123,
      "modifierFlags" : 786432
    },
    "maximize" : {
      "keyCode" : 36,
      "modifierFlags" : 786432
    },
    "maximizeHeight" : {
      "keyCode" : 126,
      "modifierFlags" : 917504
    },
    "nextDisplay" : {
      "keyCode" : 124,
      "modifierFlags" : 1835008
    },
    "previousDisplay" : {
      "keyCode" : 123,
      "modifierFlags" : 1835008
    },
    "restore" : {
      "keyCode" : 51,
      "modifierFlags" : 786432
    },
    "rightHalf" : {
      "keyCode" : 124,
      "modifierFlags" : 786432
    },
    "smaller" : {
      "keyCode" : 27,
      "modifierFlags" : 786432
    },
    "topHalf" : {
      "keyCode" : 126,
      "modifierFlags" : 786432
    },
    "topLeft" : {
      "keyCode" : 32,
      "modifierFlags" : 786432
    },
    "topRight" : {
      "keyCode" : 34,
      "modifierFlags" : 786432
    }
  },
  "version" : "59"
}
```

## Dotfiles (git, zsh)

## Alfred

## iTerm

## Static Documentation Website
```shell
➜ cat requirements.txt
mkdocs>=1.3.0
mkdocs-material>=8.2.11
mkdocs-pdf-export-plugin>=0.5.10
mkdocs-exclude>=1.0.2
mkdocs-markmap>=2.2.0
```

```shell
➜ cat mkdocs.yml
```
```json
site_name: Drew Meyers' Notes
docs_dir: ./docs

theme:
  name: material
  palette:
    - media: "(prefers-color-scheme: light)"
      scheme: default
      toggle:
        icon: material/weather-night
        name: Switch to dark mode
      primary: black
      accent: red

    - media: "(prefers-color-scheme: dark)"
      scheme: slate
      toggle:
        icon: material/weather-sunny
        name: Switch to light mode
      primary: black
      accent: red
  logo: 0 Meta/30-39 src/30 images/jpl_logo.png
  favicon: 0 Meta/30-39 src/30 images/rocket_emoji.png

markdown_extensions:
  - pymdownx.highlight:
      anchor_linenums: true
  - pymdownx.tasklist:
      custom_checkbox: true
  - admonition
  - pymdownx.inlinehilite
  - pymdownx.snippets
  - pymdownx.superfences
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.caret
  - pymdownx.keys
  - pymdownx.mark
  - pymdownx.tilde

plugins:
  - search
  - pdf-export:
      verbose: true
      media_type: print
      enabled_if_env: ENABLE_PDF_EXPORT
  - exclude:
      glob:
        #- 0 Meta/Priv/*
  - markmap

# Encountered issue with pdf-export plugin, the first page of each PDF is blank.
# https://github.com/zhaoterryy/mkdocs-pdf-export-plugin/issues/87
extra_css:
  - 0 Meta/30-39 src/31 stylesheets/extra.css
```

```shell
➜ cat docs/0\ Meta/30-39\ src/31\ stylesheets/extra.css
```
```css
.md-main__inner {
  height: 0% !important;
}
```
