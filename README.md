# Pomme Notes
Latest release: 1.5
Updated: 2025-09-05

This is a lightweight subtle theme to harmonize with macOS and iOS environments.
Some smooth animations and smooth fade-ins for embedded PDFs and Images make it look quite pleasing to use.

This theme respects custom accent color and applies it throughout the theme, including links, checkboxes, and even Iconize's default color.

Recommended plugins are:
- Iconize
- Iconic
- Better Search Views
- Daily Note Calendar
- Zen Mode

## Screenshots
![](https://github.com/MrParalloid/pomme-notes/blob/main/images/main.jpg)

## Some features:
- Smooth experience and native look & feel on Apple devices
- Optimized for Retina displays
- Dark and light modes
- Full-size YouTube embeds
- Minimal embeds that blend inside the notes
- Styled checkboxes
- Custom checkboxes by Kepano
- Smooth fade-in animations for keyframes and menus
- Iconize default color is taken from the color-accent variable
- Safari Tabs style by gavinmn with some extras
- Customized Mobile looks, including bigger buttons and comfortable file navigation
- Customized built-in tables and Dataview tables to match macOS style
- Full black background options per device (via Style Settings)
- Proper tab bar size on iPads
- Ability to switch Mobile Action Bar style to pre-1.9 version

## Recommended Settings for Iconize
Add custom rule based on regex to find all non-markdown files and assign a paperclip 📎 icon to them: 

```
^(?!.*\.md$).*
```
This way you'll see all attachments and files marked differently from regular notes and folders.
For .base files introduced in 1.9 you can use this regex:
```
^.*\.(base)$
```
