Catppuccin Macchiato Theme for Kitty

🎨 Color Scheme
The theme uses the beloved Catppuccin Macchiato palette:

Purpose	Color	Sample
Background	#1E1E2E	https://via.placeholder.com/15/1E1E2E/000000?text=+
Foreground	#CDD6F4	https://via.placeholder.com/15/CDD6F4/000000?text=+
Active Tab	#CBA6F7	https://via.placeholder.com/15/CBA6F7/000000?text=+
Red	#F38BA8	https://via.placeholder.com/15/F38BA8/000000?text=+
Green	#A6E3A1	https://via.placeholder.com/15/A6E3A1/000000?text=+
Yellow	#F9E2AF	https://via.placeholder.com/15/F9E2AF/000000?text=+
Blue	#89B4FA	https://via.placeholder.com/15/89B4FA/000000?text=+

✨ Features
Font: Adwaita Mono (size 14.0)

Transparency: background_opacity: 0.4

Cursor trail effect: cursor_trail: 3

Complete Catppuccin Macchiato palette for all 16 terminal colors

Beautiful tab bar with purple active tabs and dark inactive tabs

Optimized for readability and long coding sessions

🚀 Installation
Method 1: Direct Download
Download the kitty.conf file from this repository

Replace your existing Kitty configuration:

bash
cp kitty.conf ~/.config/kitty/kitty.conf
Method 2: Include in Existing Config
Add this line to your existing ~/.config/kitty/kitty.conf:

conf
include /path/to/this/kitty.conf
Method 3: Git Clone
bash
git clone https://github.com/YOUR_USERNAME/kitty-catppuccin-macchiato.git
cd kitty-catppuccin-macchiato
cp kitty.conf ~/.config/kitty/
Restart Kitty or reload config with Ctrl+Shift+F5

⚙️ Customization
Transparency
Adjust the background transparency to your preference:

conf
background_opacity 0.8    # More opaque
background_opacity 0.2    # More transparent
Font
Change the font to your preferred monospace font:

conf
font_family JetBrainsMono Nerd Font
font_size 12.0
Cursor
Uncomment and customize cursor settings:

conf
cursor #6022F5
cursor_shape block
cursor_blink_interval 0.5
🖼️ Preview
(Add a screenshot of your terminal showing the theme in action)

bash
# Example commands to show the color scheme
ls -la
git status
npm install
🔧 Requirements
Kitty Terminal v0.20.0 or newer

Adwaita Mono font (or any other monospace font)

🎯 Recommended Setup
For the best experience, pair this theme with:

Catppuccin GTK Theme

Catppuccin VS Code Theme

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
