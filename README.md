# JsonConverter

A small web tool that turns a JSON backup file into clean, readable markdown. Drop in an export from one of my other tools (or any JSON file) and get markdown you can copy into notes or download as a `.md` file.

## How it works

1. Drop a JSON file on the page, or click to choose one.
2. The tool detects which kind of export it is and shows a badge (unknown files fall back to a generic converter that handles any valid JSON).
3. The markdown appears in a text box, ready to copy or download.

## Privacy

Everything happens in your browser. The file is never uploaded anywhere: there is no server, no analytics, no cookies, and nothing is saved between visits. Close or reload the page and the data is gone.

## Running it

It is a single `index.html` file with no dependencies. Open it in any modern browser, or visit the GitHub Pages site for this repository.
