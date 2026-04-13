<p align="center">
  <img src="https://raw.githubusercontent.com/mateCreations/yerba-mate.nvim/master/images/logo.png" alt="Yerba Mate" width="80" />
</p>

<h1 align="center">Yerba Mate for Neovim</h1>

<p align="center">
  <em>Deep olive-black, earthy accents, mate-green strings.</em>
</p>

<p align="center">
  <a href="#variants">Variants</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#palette">Palette</a> ·
  <a href="https://github.com/mateCreations">mateCreations</a>
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/mateCreations/yerba-mate.nvim/master/images/preview.png" alt="Yerba Mate for Neovim" width="90%" />
</p>

## Variants

| Variant | Background | Description |
|---------|-----------|-------------|
| `yerba-mate` | <img src="https://placehold.co/16x16/1c1e13/1c1e13" /> `#1c1e13` | Dark — olive-black, earthy accents |
| `terere` | <img src="https://placehold.co/16x16/fbf1c7/fbf1c7" /> `#fbf1c7` | Light — butter-paper, amber accents |

## Installation

### lazy.nvim

```lua
{
  "mateCreations/yerba-mate.nvim",
  priority = 1000,
  config = function()
    vim.cmd("colorscheme yerba-mate") -- or "terere"
  end,
}
```

### lazy.nvim + LazyVim

```lua
{
  "LazyVim/LazyVim",
  opts = {
    colorscheme = "yerba-mate", -- or "terere"
  },
}
```

## Palette

### Yerba Mate (dark)

| Color | Hex | Role |
|-------|-----|------|
| <img src="https://placehold.co/16x16/1c1e13/1c1e13" /> **Background** | `#1c1e13` | Olive-black base |
| <img src="https://placehold.co/16x16/dce0d9/dce0d9" /> **Foreground** | `#dce0d9` | Silver-gray text |
| <img src="https://placehold.co/16x16/c25d44/c25d44" /> **Red** | `#c25d44` | Terracotta, keywords |
| <img src="https://placehold.co/16x16/8fb339/8fb339" /> **Green** | `#8fb339` | Mate-green, strings |
| <img src="https://placehold.co/16x16/7eb2d1/7eb2d1" /> **Blue** | `#7eb2d1` | Metal-blue, functions |
| <img src="https://placehold.co/16x16/a67c52/a67c52" /> **Ochre** | `#a67c52` | Earthy accent, types |
| <img src="https://placehold.co/16x16/4f5b4a/4f5b4a" /> **Comments** | `#4f5b4a` | Dark moss |

### Terere (light)

| Color | Hex | Role |
|-------|-----|------|
| <img src="https://placehold.co/16x16/fbf1c7/fbf1c7" /> **Background** | `#fbf1c7` | Butter-paper base |
| <img src="https://placehold.co/16x16/3c3836/3c3836" /> **Foreground** | `#3c3836` | Charcoal text |
| <img src="https://placehold.co/16x16/9d0006/9d0006" /> **Red** | `#9d0006` | Terracotta, keywords |
| <img src="https://placehold.co/16x16/79740e/79740e" /> **Green** | `#79740e` | Dense olive, strings |
| <img src="https://placehold.co/16x16/076678/076678" /> **Blue** | `#076678` | Petroleum-blue, functions |
| <img src="https://placehold.co/16x16/b57614/b57614" /> **Amber** | `#b57614` | Golden accent, types |
| <img src="https://placehold.co/16x16/928374/928374" /> **Comments** | `#928374` | Taupe gray |

## Plugin Support

Editor UI, Treesitter, LSP diagnostics, GitSigns, Telescope, Snacks, nvim-cmp, Which-key, Lazy.nvim, Alpha/Dashboard.

## Mate Theme Family

| App | Repository |
|-----|------------|
| **Omarchy (dark)** | [mateCreations/omarchy-yerba-mate](https://github.com/mateCreations/omarchy-yerba-mate) |
| **Omarchy (light)** | [mateCreations/omarchy-terere](https://github.com/mateCreations/omarchy-terere) |
| **VS Code** | [mateCreations/vscode-yerba-mate](https://github.com/mateCreations/vscode-yerba-mate) |
| **Obsidian** | [mateCreations/obsidian-yerba-mate](https://github.com/mateCreations/obsidian-yerba-mate) |
| **Zen Browser** | [mateCreations/zen-yerba-mate](https://github.com/mateCreations/zen-yerba-mate) |
| **LibreWolf** | [mateCreations/librewolf-yerba-mate](https://github.com/mateCreations/librewolf-yerba-mate) |

MIT
