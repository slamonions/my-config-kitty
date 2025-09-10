# ✨ My Kitty Config  

> 🎨 A sleek, customizable configuration for the [Kitty](https://sw.kovidgoyal.net/kitty/) terminal, featuring the vibrant Dracula color scheme, Nerd Fonts, and user-friendly settings for a modern terminal experience.

---

## 🚀 Features  

- 🔤 Nerd Fonts Support: Optimized for fonts like FiraCode Nerd Font for enhanced glyph rendering.  
- 🪟 Transparent Window: Subtle transparency for a modern, immersive look.  
- ⌨️ Efficient Hotkeys: Streamlined shortcuts for faster navigation and productivity.  
- 🎯 Clean UI: Minimalist cursor design and optimized padding for a clutter-free interface.  

---

## 🛠 Installation  

1. Install Kitty: Ensure [Kitty](https://sw.kovidgoyal.net/kitty/) is installed on your system.  
   - On macOS: brew install kitty  
   - On Linux: sudo apt install kitty (or use your package manager)  
   - On Windows: Use the [official installer](https://sw.kovidgoyal.net/kitty/binary.html).  

2. Copy the Configuration:  
      mkdir -p ~/.config/kitty
   cp kitty.conf ~/.config/kitty/
   

3. Apply Changes: Restart Kitty or open a new terminal window to load the configuration.

4. Optional - Install Nerd Fonts:  
   - Download and install [FiraCode Nerd Font](https://www.nerdfonts.com/font-downloads).  
   - Update kitty.conf to use it (see [Customization](#%F0%9F%94%A7-customization) below).

---

## 🔧 Customization  

Personalize your Kitty terminal by modifying kitty.conf in ~/.config/kitty/. Below are some common tweaks:

- Font Size: Adjust font_size for readability (e.g., font_size 14).  
- Transparency: Change background_opacity (e.g., background_opacity 0.85 for more/less transparency).  
- Cursor Style: Set cursor_shape to block, beam, or underline.  
- Padding: Modify window_padding_width for more/less spacing (e.g., window_padding_width 10).  
- Colors: Customize the Dracula palette by editing foreground, background, or other color settings.
- Markdown Rendering: Enable Markdown preview with map ctrl+shift+m kitten hints --type=markdown.

Example:
font_size 14
background_opacity 0.9
cursor_shape beam
window_padding_width 8
map ctrl+shift+m kitten hints --type=markdown

Restart Kitty after making changes to apply them.

---

## 📸 Screenshots
## Basic
![Kitty Terminal with Basic Theme](https://github.com/user-attachments/assets/424fcbd0-8ad1-4150-a503-c49ca80cc332)
## Dracula
<img width="1018" height="540" alt="Image" src="https://github.com/user-attachments/assets/5ac5ce96-043e-47bb-a7c9-9c490787a4df" />

## Gruvbox Dark
<img width="1020" height="542" alt="Image" src="https://github.com/user-attachments/assets/c0486bd0-99e1-46ba-a890-36faf01c726d" />

## Tokyo Night
<img width="1019" height="541" alt="Image" src="https://github.com/user-attachments/assets/4046df0c-25f9-4ba2-a87e-dbfb374274c8" />


## 📝 Notes  

- Ensure your system supports transparency (compositing must be enabled).  
- For Markdown rendering, ensure Kitty’s kitten tool is available (included by default).  
- For advanced hotkey customization or Markdown features, refer to Kitty’s [official documentation](https://sw.kovidgoyal.net/kitty/actions/).  
- If Nerd Fonts or Markdown don’t render correctly, verify the font is installed and specified in kitty.conf.

## 📄 License

The project is distributed under the [MIT](LICENSE) license.
