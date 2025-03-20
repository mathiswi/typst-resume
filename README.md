# Typst CV Template

A clean, modern CV/resume template created with [Typst](https://typst.app/).

## Files

- `template.typ`: Contains all the styling and layout functions
- `cv-showcase.typ`: A demo/showcase version with dummy data that can be published or shared
- `cv-personal.typ`: Your personal CV (kept in sync with a copy in the parent directory)
- `.github/workflows/compile-typst.yml`: GitHub Actions workflow to compile and deploy PDFs

## Features

- Clean, modern design
- Responsive layout
- Customizable sections
- Skills categorization with a two-column layout
- FontAwesome icons for contact information
- Support for multiple languages
- Automatic compilation via GitHub Actions

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

## GitHub Actions Workflow

This repository includes a GitHub Actions workflow that:

1. Automatically compiles the showcase CV when changes are pushed to main
2. Uploads the compiled PDF as a workflow artifact
3. Deploys the PDF to GitHub Pages (enabling online viewing)

The workflow only compiles the showcase version (`cv-showcase.typ`), not the personal CV, ensuring your private information isn't published.

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

