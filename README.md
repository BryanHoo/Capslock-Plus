# Mac Capslock Plus

> It is modeled on capslock+ of windows platform and basically keeps the same as that of windows,Click to view [windows Capslock+](https://cjkis.me/capslock+/)

## Platforms

- CapsLock-Plus via [Karabiner-Elements](https://pqrs.org/osx/karabiner/)
  - macOS Catalina(10.15)
  - macOS Mojave(10.14)
  - macOS High Sierra (10.13)
  - macOS Sierra (10.12)
  - macOS EI Capitan (10.11)

## Install

1. Download [Karabiner-Elements](https://pqrs.org/osx/karabiner/) and Install
2. Copy URL to your browser to import configuration script.

```
# This Repo (open in safari)
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/BryanHoo/Capslock-Plus/master/capslock-plus.json
```

3. Open Karabiner, Tab "ComplexModification", Button "Add Item", and enable entries you like.
4. Default conf file path is `$HOME/.config/karabiner/assets/complex_modifications`. Modify it if you like.
5. Enable functions: `[App] karabiner-elements -> [Tab] Complex Modification -> Add Item`

## Usage

### Basic

`✱` Hyper actually maps to `⌃⌥⇧⌘` (all right modifiers) , It works well with additional left modifiers. And compatible with most application. Hold CapsLock to enable `Hyper` funcationality while press it will emit an `Escape`.

> NOTE: left-shift maps to left-control + spacebar, click left-shift to switch input method by default

| Origin | Maps to    | Comment                    |
| ------ | ---------- | -------------------------- |
| Press  | `⎋` Escape | Single press to escape     |
| Hold   | `✱` Hyper  | Enable Hyper Functionality |

### navigation

Hold `✱` Hyper to enable navigators

| Origin | Maps to        | Comment                                    |
| ------ | -------------- | ------------------------------------------ |
| `S`    | `←` LeftArrow  | cursor left                                |
| `D`    | `↓` DownArrow  | cursor down                                |
| `E`    | `↑` UpArrow    | cursor up                                  |
| `F`    | `→` RightArrow | cursor right                               |
| `A`    |                | cursor skip words forward                  |
| `G`    |                | cursor skips the word backward             |
| `Y`    | `⇞` PageUp     | cursor page up                             |
| `B`    | `⇟` PageDn     | cursor page down                           |
| `P`    | `↖` Home       | cursor to line(doc) head                   |
| `;`    | `↘` End        | cursor to line(doc) end                    |
| `J`    |                | cursor left and selection                  |
| `K`    |                | cursor down and selection                  |
| `I`    |                | cursor up and selection                    |
| `L`    |                | cursor left and selection                  |
| `H`    |                | cursor one word to the left and selection  |
| `N`    |                | cursor one word to the right and selection |
| `U`    |                | cursor to line(doc) head and selection     |
| `O`    |                | cursor to line(doc) end and selection      |

### Switch Input Method

| Origin       | Maps to    | Comment             |
| ------------ | ---------- | ------------------- |
| `Left-Shift` | `CapsLock` | Switch Input Method |

### Window Control

| Origin  | Maps to                | Comment                     |
| ------- | ---------------------- | --------------------------- |
| `/` Tab | `⌘⇥` Command+Tab       | Switch Window               |
| `W`     | LeftControl+LeftArrow  | Move one space to the left  |
| `R`     | LeftControl+RightArrow | Move one space to the right |

### Applications

| Origin | Maps to     | Comment                        |
| ------ | ----------- | ------------------------------ |
| `M`    | Open Finder | Open File Browser              |
| `T`    | Open iTerm2 | Great terminal for osx (`Run`) |
