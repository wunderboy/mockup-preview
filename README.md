# mockup-preview

This tool allows you to preview your design mock-ups in your web browser easily.

## Usage

*mockup-preview* loads an external image file and adjusts cascade style sheets to display it correctly. It does so by following rules:

1. If `src` parameter is specified, it tries to load this file, e.g. `index.html?src=mockup.png` will try to load `mockup.png`.
2. Otherwise, it tries to load a *.png file based on current document name, e.g. `index.html` will try to load `index.png`.