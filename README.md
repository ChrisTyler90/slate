# Slate
A framework using scss

# Getting Started
## SCSS
Copy the contents of the `scss` folder to your project.
You are free to keep the files within another folder (i.e. /vendor/slate), but files within this directory must remain.

## JS
Include the bundled `slate.js` from the `js` folder as part of your project.

## HTML
It is recommended to add the following line to the `<head>` of your document:

`<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />`

# Dependencies
Slate assumes that you have a relative up-to-date version of SCSS installed (compiled with 3.4.18)

# Configuration
Variables for slate can be found in the `var.scss` file:

| Variable | Default | Usage |
| ---- | ---- | ---- |
| $grid-container-width | 75rem | The maximum width of a centered row |
| $grid-column-count | 12 | Maximum number of columns in a row |
| $grid-breakpoints | (<br />&nbsp;&nbsp;&nbsp;&nbsp;small: 0,<br />&nbsp;&nbsp;&nbsp;&nbsp;medium: 48rem,<br />&nbsp;&nbsp;&nbsp;&nbsp;large: 64rem<br />) | An associative array of the size name, and it's min-width |
| $grid-gutter | (<br />&nbsp;&nbsp;&nbsp;&nbsp;small: .625rem,<br />&nbsp;&nbsp;&nbsp;&nbsp;medium: 1.25rem,<br />&nbsp;&nbsp;&nbsp;&nbsp;large: 2.5rem<br />) | The gutter widths, for each of the `$grid-breakpoints`