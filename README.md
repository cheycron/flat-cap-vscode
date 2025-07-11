<p align="center">
  <img src="https://github.com/cheycron/flat-cap-theme/blob/main/images/readme_logo.png?raw=true" alt="flatcap"/>
</p>

<p align="center">
  Flat Cap is a dark, minimalist, and eye-friendly theme for Visual Studio Code, meticulously crafted to provide a comfortable and focused coding experience.
</p>

[![BuyMeACoffee](https://raw.githubusercontent.com/pachadotdev/buymeacoffee-badges/main/bmc-blue.svg)](https://www.buymeacoffee.com/cheycron)

<p align="center">
  <img src="https://github.com/cheycron/flat-cap-theme/blob/main/images/demo_vscode.png?raw=true" alt="Flatcap VSCode"/>
</p>

## Sintaxis Highlight

<p align="center">
  <img src="images/flat-cap-go.png?raw=true" alt="Flatcap VSCode"/>
  <img src="images/flat-cap-rust.png?raw=true" alt="Flatcap VSCode"/>
</p>

<p align="center">
  <img src="images/flat-cap-php.png?raw=true" alt="Flatcap VSCode"/>
  <img src="images/flat-cap-js.png?raw=true" alt="Flatcap VSCode"/>
</p>

## Installation

1.  Open **Visual Studio Code**.
2.  Go to the **Extensions** view (`Ctrl+Shift+X`).
3.  Search for `Flat Cap`.
4.  Click **Install** to apply the theme.
5.  Set the theme by going to `File > Preferences > Color Theme` and selecting **Flat Cap**.

## Philosophy

Flat Cap draws inspiration from the fantastic design logic of the **[Nord theme](https://github.com/nordtheme/nord)**, embracing its principles of calm, clean aesthetics, and a dimmed pastel color approach. However, Flat Cap diverges significantly in its color palette, which is uniquely derived from the visual language of the latest **Horizon OS** iterations by Meta for Oculus Quest. This fusion results in a theme that is both familiar in its minimalist comfort and fresh in its distinct, modern color scheme.

## Color Palette

The Flat Cap theme is built upon a carefully curated and expanded color palette, designed for granular control and visual harmony across various UI elements and syntax highlighting. The palette is divided into four main categories: Deep Twilight, Dawnlight, Ocean Blues, and Vivid Accents.

<p align="center">
  <img src="https://github.com/cheycron/flat-cap-theme/blob/main/images/color_deeptwilight.png?raw=true" alt="Deep Twilight"/>
</p>
<p align="center">
  <img src="https://github.com/cheycron/flat-cap-theme/blob/main/images/color_dawnlight.png?raw=true" alt="Dawnlight"/>
</p>
<p align="center">
  <img src="https://github.com/cheycron/flat-cap-theme/blob/main/images/color_oceanblues.png?raw=true" alt="Ocean Blues"/>
</p>
<p align="center">
  <img src="https://github.com/cheycron/flat-cap-theme/blob/main/images/color_vividaccents.png?raw=true" alt="Vivid Accents"/>
</p>

### Deep Twilight (Dark Backgrounds & Base Elements)

These colors are primarily used for backgrounds, elevated UI elements, and low-priority components in dark ambiance designs.

- **FlatCap 0**: `#1c1e22` - Interface base, the darkest tone.
- **FlatCap 1**: `#23262b` - Secondary panel backgrounds, subtle UI elements.
- **FlatCap 2**: `#2d3036` - Elevated UI element backgrounds, active editor lines, containers.
- **FlatCap 3**: `#373a40` - Borders, separators, code comments, secondary text.
- **FlatCap 4**: `#42474e` - Subtle shadows, semi-transparent overlays, highly muted text.

### Dawnlight (Light Text & UI Elements)

Perfect for main text, contrasting UI elements, and light backgrounds.

- **FlatCap 5**: `#d0d2d6` - Low-contrast text in dark mode.
- **FlatCap 6**: `#e4e6eb` - Main text in dark mode, clear UI elements.
- **FlatCap 7**: `#ecedf0` - Light container backgrounds, interactive UI elements.
- **FlatCap 8**: `#f4f5f7` - Brightest tone for light base backgrounds, maximum highlights.
- **FlatCap 9**: `#fcfdff` - Very specific elements requiring highest contrast or purity, like light mode selection highlights.

### Ocean Blues (Primary UI Components & Syntax)

The core of the palette, used for key UI components and code syntax, now with a more noticeable tonal progression.

- **FlatCap 10**: `#6b7f8e` - Darker grayish-blue, for less prominent syntax elements or informational UI.
- **FlatCap 11**: `#7a90a2` - Medium blue for classes and operators, primary buttons.
- **FlatCap 12**: `#8ea5b9` - Lighter and more distinctive blue for variables and selection highlights.
- **FlatCap 13**: `#a3bbce` - Bright blue for strings, numbers, or active links, enhancing visibility.
- **FlatCap 14**: `#b8d1e3` - Softer, ethereal blue, for decorative elements or very subtle colored backgrounds.

### Vivid Accents (States & Special Syntax)

Used to indicate various states (error, warning, success) and to highlight specific syntax elements.

- **FlatCap 15**: `#e06c75` (Error) - Red for error messages.
- **FlatCap 16**: `#d19a66` (Warning) - Orange for warnings.
- **FlatCap 17**: `#98c379` (Success) - Green for success indications.
- **FlatCap 18**: `#c678dd` (Information) - Purple for informational messages.
- **FlatCap 19**: `#56b6c2` (Highlight) - Cyan for syntax highlighting, prominent visual accents.

## Recommended Settings

For the best experience, I recommend using a font that supports ligatures, such as **Fira Code** or **JetBrains Mono**. You can enable ligatures in your `settings.json`:

```json
{
  "editor.fontFamily": "'Fira Code', 'JetBrains Mono', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true
}
```
