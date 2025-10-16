# ⚡ Tmux Configuration & Plugin Setup

![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-stable-blue?style=flat-square)
![Platform](https://img.shields.io/badge/platform-linux%20%7C%20macos-lightgrey?style=flat-square)
![tmux](https://img.shields.io/badge/tmux-%3E%3D3.0-brightgreen?style=flat-square)

> 🚀 A clean, customizable, and plugin-friendly Tmux setup designed for developers who live in the terminal.

---

## 🧩 1. Copy the Configuration

Create or edit your Tmux configuration file:

```bash
vim ~/.tmux.conf
# or
nvim ~/.tmux.conf
```

Paste your custom config into the file, then save and exit.

---

## 🔧 2. Install the Tmux Plugin Manager (TPM)

Clone the **TPM** repository to manage your plugins easily:

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

---

## 🚀 3. Start or Reload Tmux

Start a new Tmux session:
```bash
tmux new -s huh
```

If Tmux is already running, reload your configuration:
```bash
tmux source ~/.tmux.conf
```

---

## 📦 4. Install Plugins

Add plugins to your `~/.tmux.conf` file like this:

```bash
set -g @plugin 'tmux-plugins/tmux-sensible'
set -g @plugin 'tmux-plugins/tmux-resurrect'
set -g @plugin 'tmux-plugins/tmux-continuum'
```

Then press your **prefix key + I**  
(that’s a capital “I”, as in *Install*) to download and activate them.

---

## 🧠 Prefix Key

The default prefix key in this config is set to:
```
Ctrl + s
```

If you prefer something else (like the default `Ctrl + b`), update this line in your `~/.tmux.conf`:

```bash
set -g prefix C-s
```

---

## 🧰 Recommended Plugins

| Plugin | Description |
|--------|--------------|
| [`tmux-plugins/tmux-sensible`](https://github.com/tmux-plugins/tmux-sensible) | Smart default settings for Tmux |
| [`tmux-plugins/tmux-resurrect`](https://github.com/tmux-plugins/tmux-resurrect) | Save and restore Tmux sessions |
| [`tmux-plugins/tmux-continuum`](https://github.com/tmux-plugins/tmux-continuum) | Continuous saving + auto-startup |
| [`tmux-plugins/tmux-yank`](https://github.com/tmux-plugins/tmux-yank) | Copy text from Tmux to system clipboard |
| [`tmux-plugins/tmux-prefix-highlight`](https://github.com/tmux-plugins/tmux-prefix-highlight) | Show status when prefix key is pressed |
| [`tmux-plugins/tmux-battery`](https://github.com/tmux-plugins/tmux-battery) | Display battery status in the status bar |

---

## 🖥️ Demo Preview

![Tmux_Demo](https://github.com/Anganba/ImagesHostedOnGitHub/blob/1b5523a21bcb9b26acd348def8a813b9a2097ca8/tmux.png)

---

## ✅ You’re Good to Go!

Your Tmux is now fully configured with TPM support.  
Plugins are stored in:
```
~/.tmux/plugins/
```

To update plugins later, just press:
```
prefix + U
```

> 🦄 *Hack, code, and multitask in style — welcome to your new terminal superpower.*

---

### 🧡 Credits

Built with love using [Tmux](https://github.com/tmux/tmux) and [TPM](https://github.com/tmux-plugins/tpm).  
Maintained by the community — PRs and stars are always welcome ⭐
