# DESY open day playground

This is an adaptation of [tensorflows' playground](https://github.com/tensorflow/playground).
Designed for DESY to present in the Open Day by Henry Day-Hall, with physics data supplied by Konrad Helms.


## Development

To run the visualization locally, run:
- `npm i` to install dependencies
- `npm run build` to compile the app and place it in the `dist/` directory
- `npm run serve` to serve from the `dist/` directory and open a page on your browser.

For a fast edit-refresh cycle when developing run `npm run serve-watch`.
This will start an http server and automatically re-compile the TypeScript,
HTML and CSS files whenever they change.

