# Vagabond RPG Fonts

This directory contains the custom fonts for the Vagabond RPG system to match the book's typography.

## Required Fonts

You need to obtain and place the following font files in this directory:

### 1. Eskapade by Alisa Nowak
- `Eskapade-Regular.woff2` / `.woff` / `.otf`
- `Eskapade-Bold.woff2` / `.woff` / `.otf`
- **Used for**: Body text, descriptions, general content

### 2. Manofa by Mariya Lish and Inhouse Type Foundry
- `Manofa-Regular.woff2` / `.woff` / `.otf`
- `Manofa-Bold.woff2` / `.woff` / `.otf`
- **Used for**: Headers, section titles

### 3. Paradigm Pro by Nick Shinn
- `ParadigmPro-Regular.woff2` / `.woff` / `.otf`
- `ParadigmPro-Bold.woff2` / `.woff` / `.otf`
- **Used for**: Stats, labels, secondary text

### 4. timeTo by Speak the Sky
- `timeTo-Regular.woff2` / `.woff` / `.otf`
- `timeTo-Bold.woff2` / `.woff` / `.otf`
- **Used for**: Display elements, special text

## File Format Priority

The CSS will try to load fonts in this order:
1. `.woff2` (best compression, modern browsers)
2. `.woff` (good compatibility)
3. `.otf` (OpenType, universal fallback)

You can provide all three formats or just one. WOFF2 is recommended for best performance.

## Fallback Fonts

If the custom fonts are not available, the system will fall back to Google Fonts (Crimson Pro and Oswald) automatically.

## Installation

1. Download the font files from their respective sources
2. Convert to web formats (.woff2, .woff) if necessary using a tool like [Transfonter](https://transfonter.org/)
3. Place the files in this directory (`styles/fonts/`)
4. Ensure the filenames match those listed above
5. Refresh Foundry VTT to see the new fonts

## License Note

Make sure you have the proper licenses for these fonts before using them in your game. Some fonts may require commercial licenses for use in published content.
