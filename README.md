# Pocket Tasks

A tiny offline to-do list. Add tasks, mark them complete, filter the list, and clear finished items. The interface is in Simplified Chinese.

## Run

Download this repository and open `index.html` in a modern browser. There is no build step, package installation, or account requirement.

Alternatively, serve the folder locally:

```sh
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Features

- Add tasks up to 300 characters.
- Toggle completion, filter active or finished tasks, and remove individual items.
- Keep tasks in local storage under `pocket-tasks:v1`.
- Work without any network requests or external dependencies.
- Render task text as text rather than HTML.

## Storage and privacy

No data is sent to a server. Clearing browser storage removes the saved list. File-based local storage can behave differently across browsers; if saving is unavailable, the current page remains usable and shows a warning. This is a simple personal list, not encrypted storage: do not enter secrets.

## Development

All application code and styles are in `index.html`. Edit the file and refresh your browser. Files use UTF-8.

## License

MIT. See [LICENSE](LICENSE).
