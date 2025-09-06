# Tmux Configuration Shortcuts Reference

## Prefix Key
- **Prefix**: `Ctrl-a` (instead of default `Ctrl-b`)

## Session Management
- `Ctrl-a R` - Rename session
- `Ctrl-a Q` - Kill current session (with confirmation)
- `Ctrl-a d` - Detach from session
- `Ctrl-a D` - Detach other clients (if multiple attached)
- `Ctrl-a C-u` - Merge current session with another (move all windows)

## Window Management
- `Ctrl-a c` - Create new window (retaining current path)
- `Ctrl-a r` - Rename current window
- `Ctrl-a x` - Kill current pane
- `Ctrl-a X` - Kill current window
- `Ctrl-a C-x` - Kill all other windows (with confirmation)
- `Ctrl-a C-[` - Previous window
- `Ctrl-a C-]` - Next window
- `Ctrl-a Tab` - Cycle through most recently used windows
- `Ctrl-a L` - Link window from another session

## Pane Management
- `Ctrl-a |` - Split pane horizontally (retain current path)
- `Ctrl-a _` - Split pane vertically (retain current path)
- `Ctrl-a h` - Select left pane
- `Ctrl-a j` - Select bottom pane
- `Ctrl-a k` - Select top pane
- `Ctrl-a l` - Select right pane
- `Ctrl-a [` - Select previous pane
- `Ctrl-a ]` - Select next pane
- `Ctrl-a C-o` - Swap pane with next one
- `Ctrl-a \` - Swap pane with first pane
- `Ctrl-a +` - Zoom/unzoom current pane

## Copy Mode (Vi-style)
- `Ctrl-a M-Up` - Enter copy mode
- `Mouse wheel` - Scroll in copy mode (2 lines per tick)
- `M-Up/Down` - Scroll up/down by 1 line
- `M-PageUp/Down` - Scroll half page up/down
- `PageUp/Down` - Scroll full page up/down
- `Enter/y` - Copy selection and exit copy mode
- `Y` - Copy entire line
- `D` - Copy to end of line
- `C-j` - Copy selection and exit copy mode
- `A` - Append selection to buffer

## Configuration & Reload
- `Ctrl-a C-e` - Edit tmux.conf in new window
- `Ctrl-a C-r` - Reload tmux configuration

## Status Bar & Display
- `Ctrl-a C-s` - Toggle status bar visibility
- `F12` - Toggle local/remote session mode (pass-through keys)

## Monitoring
- `Ctrl-a m` - Toggle window activity monitoring
- `Ctrl-a M` - Set window silence monitoring (specify interval)

## Paste & Buffers
- `Ctrl-a p` - Paste from buffer
- `Ctrl-a C-p` - Choose buffer to paste from

## Special Features
- **Mouse support**: Enabled for pane selection, resizing, and scrolling
- **Activity monitoring**: Visual alerts for active windows
- **Battery status**: Displayed in status bar
- **System stats**: CPU, memory, load average in status bar
- **Online status**: Shows internet connectivity
- **Zoom indicator**: `[Z]` shown when pane is zoomed

## Plugin Shortcuts
- **Sidebar**: `prefix-t` (toggle), `prefix-T` (focus)
- **Copycat**: Search functionality for various patterns
- **Open**: `prefix-S` to search selected text on Google

## Notes
- Windows and panes start indexing from 1 (human-friendly)
- Automatic window renaming is disabled
- Status bar shows: session name, system stats, user@host, date/time, battery
- Powerline-style separators used in status bar
- 256-color terminal support enabled