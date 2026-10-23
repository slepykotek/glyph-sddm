# glyph sddm

A high-end, minimalist SDDM theme inspired by the **Nothing Phone** aesthetic. Featuring authentic dot-matrix typography, intelligent adaptive coloring, and premium "obsidian glass" interactions.

<div align="center">
  <img src="screenshots/login_screen.png" width="45%" alt="Login Screen" />
</div>

## 🛠 configuration & Testing

### preview without logging out
Run this command to preview the theme:
```bash
# For Qt6 (Modern):
sddm-greeter-qt6 --test-mode --theme /usr/share/sddm/themes/glyph

# For Qt5 (Legacy):
sddm-greeter --test-mode --theme /usr/share/sddm/themes/glyph
```

### Customization
Edit `theme.conf` or replace assets in `assets/images/`:
- **Wallpaper:** Replace `assets/images/background.jpg`.
- **Avatar:** Replace `assets/images/avatar.jpg`.
- **Clock Format:** Set `use24HourClock=true` in `theme.conf` to switch to a 24-hour clock, or `use24HourClock=false` for 12-hour.

## 🤝 Credits

- **Author:** [xCaptaiN09](https://github.com/xCaptaiN09)
- **Design:** Inspired by Nothing Phone (1) & (2).
- **Fonts:** Ndot 57 Aligned & Symbols Nerd Font (included).
