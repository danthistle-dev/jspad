# JSPad

An in-browser JavaScript and Markdown editor. Contains support for dynamically importing most libraries from NPM. Uses a CLI and local node server to allow for data persistence.

## Libraries used

- React
- Redux
- TypeScript
- Bulma
- Express

## Install the CLI

Install globally using

`$ npm install -g jspad`

## Start the development server

Using global install 

`$ jspad serve`

or using npx (no install required)

`$ npx jspad serve`

Default port is `4005`

## CLI options

| Command              | Description           | Default       |
| -------------------- | --------------------- | ------------- |
| `--port` or `-p`     | Port to run server on | `4005`        |
| `[filename]`         | File to open          | `notebook.js` |

### Examples

1. Open new file on default port: `$ jspad serve`

2. Open existing file `example.js` on port `8000`: `$ jspad serve example.js --port 8000`

3. Open existing file in a different directory: `$ jspad serve ../test/example.js`

***

#### Thanks to Stephen Grider for the fantastic course
@ste_grider
