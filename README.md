# allapps-vimlike
## Features
You can use the keymap like Vim and EMACS at any apps on Linux.

## Keymaps
By the default setting, `Hyper` is mapped to `変換`

### Simply mapped (Mapped with XKB)
| Pushed keys | Mapped Keys | Like | Usage|
| ---- | ---- | ---- | ---- |
| Hyper + h | ← | Vim | Cursor key |
| Hyper + j | ↓ | Vim | Cursor key |
| Hyper + k | ↑ | Vim | Cursor key |
| Hyper + l | → | Vim | Cursor key |
| Hyper + ; | BackSpace | Original | Backspace |
| Hyper + : | Delete | Original | Delete |
| Hyper + a | Home | Emacs | Move cursor to the head of line |
| Hyper + e | End | Emacs | Move cursor to the end of line |
| Hyper + m | Enter | Emacs | Enter key |
| Hyper + Ctrl + [ | Esc | Vim | Esc (Mapped with AutoKey) |
| Hyper + Ctrl + @ | Esc | Vim | Esc (Mapped with AutoKey) |

### Cursor (Mapped with XKB)
| Pushed keys | Mapped Keys | Like | Usage |
| ---- | ---- | ---- | ---- |
| Hyper + Shift + b | Ctrl + ← | Vim | Move cursor to the head of word |
| Hyper + Shift + w | Ctrl + Shift + → | Vim | Secelt the range from current cursor to the head of word |
| Hyper + w | Ctrl + → | Vim | Move cursor to the end of word |
| Hyper + Shift + w | Ctrl + Shift + → | Vim | Secelt the range from current cursor to the end of word |
| Hyper + o | End -> Enter | Vim | Make a line below current cursor |
| Hyper + Shift + o | ↑ -> End -> Enter | Vim | Make a line above current cursor |

#### Shortcut (Mapped with XKB)
| Pushed keys | Mapped Keys | Like | Usage |
| ---- | ---- | ---- | ---- |
| Hyper + u | Ctrl + z | Vim | Undo |
| Hyper + Ctrl + r | Ctrl + Shift + z | Vim | Redo |
| Hyper + y | Ctrl + c | Vim | Copy |
| Hyper + Shift + y | Ctrl + End -> Ctrl + c -> → | Vim | Copy the range from current cursor to the end of line |
| Hyper + d | Ctrl + x | Vim | Cut |
| Hyper + Shift + d | Ctrl + Shift + End -> Ctrl + x | Vim | Cut the range from current cursor to the end of line |
| Hyper + p | Ctrl + v | Vim | Paste |
