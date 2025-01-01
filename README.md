# Custom Config Key Features and Shortcuts

## Tmux Window Management
* `Super + Number` - Switch to the Nth tmux window
* `Super + t` - Create a new tmux window
* `Super + r` - Rename the current tmux window
* `Super + w` - Kill the current tmux pane or the tmux window if there are no panes left

## Pane Splitting and Navigation
* `Super + -` - Create a horizontal split
* `Super + \` - Create a vertical split (*Note*: Ghostty doesn't support the pipe `|` character)
* `Super + z` - Toggle pane zoom

## Window Reordering
* `Super + i` - Move the current tmux window to the left
* `Super + o` - Move the current tmux window to the right

## Window Navigation
* `Super + h` - Move to the previous tmux window (typically to the left)
* `Super + l` - Move to the next tmux window (typically to the right)
* `Super + p` - Use `fzf` to switch to a specific tmux window (requires `tmux-fzf` plugin)

## Seamless Navigation Between tmux and Neovim
* `Ctrl + h`, `Ctrl + j`, `Ctrl + k`, `Ctrl + l` - Move between Neovim and tmux panes (requires `vim-tmux-navigator` plugin)
* `Alt + h`, `Alt + j`, `Alt + k`, `Alt + l` - Resize tmux panes

These settings streamline workflows across tmux and Neovim, making them highly efficient for development tasks.

> **Important Note:** To use Ghostty effectively, you need to disable the default macOS keyboard shortcut for hiding applications. By default, macOS assigns `Cmd + h` to hide any app, which can interfere with Ghostty's functionality.
