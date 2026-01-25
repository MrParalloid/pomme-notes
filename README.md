# Pomme Notes
Latest release: 2.0.1
Updated: 2025-01-25

This is a lightweight subtle theme to harmonize with macOS and iOS environments.
Some smooth animations and smooth fade-ins for embedded PDFs and Images make it look quite pleasing to use.

This theme respects custom accent color and applies it throughout the theme, calculating accents for Blockquotes and Highlighters.

## Screenshots
TBD

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
