**Config for Kitty terminal**

**cursor & fonts**

*Font*
```
font_family      JetBrains Maple Mono
bold_font        Maple Mono NF Bold
italic_font      Maple Mono NF Italic
bold_italic_font Maple Mono NF Medium Italic
font_size 14
modify_font cell_height 122%
```
*Cursor*
```
cursor_trail 1
cursor_trail_decay 0.1 0.2
cursor_trail_start_threshold 4
```
**Background**
```
background_opacity 0.30
```

**Keybind**
```
kitty_mod ctrl+shift

# Scrolling
map kitty_mod+up    scroll_line_up
map opt+cmd+page_up scroll_line_up
map cmd+up          scroll_line_up

map kitty_mod+down    scroll_line_down
map opt+cmd+page_down scroll_line_down
map cmd+down          scroll_line_down

map kitty_mod+k scroll_page_up
map cmd+page_up scroll_page_up

map kitty_mod+j   scroll_page_down
map cmd+page_down scroll_page_down

map kitty_mod+home scroll_home
map cmd+home       scroll_home

map kitty_mod+end scroll_end
map cmd+end       scroll_end

map kitty_mod+z scroll_to_prompt -1

# Window management
map kitty_mod+enter new_window
map cmd+enter       new_window

map ctrl+alt+enter launch --cwd=current

map kitty_mod+] next_window
map kitty_mod+[ previous_window

map kitty_mod+f move_window_forward
map kitty_mod+b move_window_backward

# Tab management
map kitty_mod+right next_tab
map shift+cmd+]     next_tab
map ctrl+tab        next_tab

map kitty_mod+left previous_tab
map shift+cmd+[    previous_tab
map ctrl+shift+tab previous_tab

map kitty_mod+t new_tab
map cmd+t       new_tab

map kitty_mod+q close_tab
map cmd+w       close_tab

map kitty_mod+. move_tab_forward
map kitty_mod+, move_tab_backward

map kitty_mod+n     set_tab_title

# Layout management
map kitty_mod+l next_layout

# Font sizes
map kitty_mod+equal  change_font_size all +1.0
map kitty_mod+plus   change_font_size all +1.0
map kitty_mod+kp_add change_font_size all +1.0
map cmd+plus         change_font_size all +1.0
map cmd+equal        change_font_size all +1.0
map shift+cmd+equal  change_font_size all +1.0

map kitty_mod+minus       change_font_size all -1.0
map kitty_mod+kp_subtract change_font_size all -1.0
map cmd+minus             change_font_size all -1.0
map shift+cmd+minus       change_font_size all -1.0

map kitty_mod+backspace change_font_size all 0
map cmd+0               change_font_size all 0
```


**Requirements**
*Kitty Terminal v0.20.0 or newer*
