## this is the SortCut Lst of Wezterm
To change the font size, modify this line:

```lua
config.font_size = 18.0
```

For example:

```lua
config.font_size = 14.0
```

or

```lua
config.font_size = 20.0
```

WezTerm accepts decimal values too, so you can use something like:

```lua
config.font_size = 16.5
```

After saving the file, either:

* Reload the config (`Ctrl + Shift + R` if the default reload binding is enabled), or
* Restart WezTerm.

---

## Your current keybindings

### 1. Toggle color scheme

```lua
CTRL + SHIFT + ALT + E
```

Press:

**Ctrl + Shift + Alt + E**

It switches between:

* `Cloud (terminal.sexy)`
* `Zenburn`

---

### 2. Split pane vertically (left/right)

```lua
CTRL + SHIFT + ALT + H
```

Press:

**Ctrl + Shift + Alt + H**

Creates a new pane on the **right**.

```
+-------+-------+
|       |       |
|       |       |
+-------+-------+
```

---

### 3. Split pane horizontally (top/bottom)

```lua
CTRL + SHIFT + ALT + V
```

Press:

**Ctrl + Shift + Alt + V**

Creates a new pane **below**.

```
+-----------+
|           |
+-----------+
|           |
+-----------+
```

---

### 4. Resize pane left

```lua
CTRL + SHIFT + U
```

Press:

**Ctrl + Shift + U**

Shrinks/grows the pane **toward the left** by 5 cells.

---

### 5. Resize pane down

```lua
CTRL + SHIFT + I
```

Press:

**Ctrl + Shift + I**

Resizes the pane **downward** by 5 cells.

---

### 6. Resize pane up

```lua
CTRL + SHIFT + O
```

Press:

**Ctrl + Shift + O**

Resizes the pane **upward** by 5 cells.

---

### 7. Resize pane right

```lua
CTRL + SHIFT + P
```

Press:

**Ctrl + Shift + P**

Resizes the pane **toward the right** by 5 cells.

---

### 8. Pane selector

```lua
CTRL + 9
```

Press:

**Ctrl + 9**

Shows labels on all panes so you can quickly jump to one.

---

### 9. Debug overlay

```lua
CTRL + L
```

Press:

**Ctrl + L**

Opens WezTerm's debug overlay.

---

### 10. Toggle window opacity

```lua
CTRL + ALT + O
```

Press:

**Ctrl + Alt + O**

Toggles between:

* `0.9` opacity (slightly transparent)
* `1.0` opacity (fully opaque)

---

## Summary

| Keys                       | Action                  |
| -------------------------- | ----------------------- |
| **Ctrl + Shift + Alt + E** | Toggle color scheme     |
| **Ctrl + Shift + Alt + H** | Split pane to the right |
| **Ctrl + Shift + Alt + V** | Split pane downward     |
| **Ctrl + Shift + U**       | Resize pane left        |
| **Ctrl + Shift + I**       | Resize pane down        |
| **Ctrl + Shift + O**       | Resize pane up          |
| **Ctrl + Shift + P**       | Resize pane right       |
| **Ctrl + 9**               | Select a pane           |
| **Ctrl + L**               | Show debug overlay      |
| **Ctrl + Alt + O**         | Toggle window opacity   |

If you're interested, I can also suggest a more ergonomic set of WezTerm keybindings (for example, using `Ctrl+a` or `Alt+h/j/k/l` like `tmux`) that many people find easier to use.

