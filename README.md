# dotbox

dotfiles: bash + vim + git, symlinked by install.sh

Side project, maintained when I have time.

## Usage

```bash
# configs are symlinked, edit here and it applies everywhere
```

## What it does

- One-command setup: ./install.sh
- Sane vim defaults, no plugins required
- Bash prompt with git branch indicator
- Git aliases I actually use daily

## Getting started

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .bashrc
├── .gitattributes
├── .gitignore
├── .vimrc
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── install.sh
```

## License

MIT - see [LICENSE](LICENSE).
