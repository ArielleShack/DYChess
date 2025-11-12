# Diamond Chess

A single-page demo rendering a standard chess position on a diamond-oriented board. Pieces are laid out using [chess.js](https://github.com/jhlywa/chess.js) for the rules engine and custom SVG rendering logic that rotates each square by −45° while spacing centers by `S / √2` to prevent gaps.

## Running

Open `index.html` in any modern browser with ES module support. No build step is required because chess.js is loaded directly from a CDN.
