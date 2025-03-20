# Typst CV Template

A clean, modern CV/resume template created with [Typst](https://typst.app/).

## Files

- `template.typ`: Contains all the styling and layout functions
- `cv-showcase.typ`: A demo/showcase version with dummy data that can be published or shared
- `cv-personal.typ`: Your personal CV (kept in sync with a copy in the parent directory)
- `sync-cv.sh`: Script to sync your CV between directories

## Features

- Clean, modern design
- Responsive layout
- Customizable sections
- Skills categorization with a two-column layout
- FontAwesome icons for contact information
- Support for multiple languages

## Usage

1. Install Typst: https://github.com/typst/typst
2. Clone this repository
3. Edit `cv-showcase.typ` with your information or create a new file
4. Compile with:

```bash
typst compile cv-showcase.typ
```

Or use the watch mode for live preview:

```bash
typst watch cv-showcase.typ
```

## Personal CV Management

This repository includes a system for managing your personal CV:

- `cv-personal.typ` in this directory is your working copy
- A copy is maintained in the parent directory (`../typst-resume-content/cv-personal.typ`)
- Use the sync script to keep them in sync:

```bash
# Copy from current directory to parent
./sync-cv.sh

# Copy from parent directory to current
./sync-cv.sh parent
```

## Customization

The template is highly customizable. You can modify:

- Colors
- Fonts and sizes
- Spacing
- Layout structure

Edit the `defaultTheme` in `template.typ` to customize the appearance.

## License

MIT

## Credits

Created by Mathis Witte 