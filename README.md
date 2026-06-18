# nomd

A minimal, local-first markdown editor that runs entirely in your browser.

**→ [nomd.dev](https://nomd.dev)**

Write markdown on the left, see it rendered on the right, and download the `.md` file when you're done. No accounts, no servers, no tracking — everything stays in your browser.

## Features

- Two-pane layout: editor on the left, live preview on the right
- Synchronized scrolling — one scroll moves both panes together
- Local-first: your work is saved in the browser, never uploaded
- One-click `.md` download
- Free, ad-free, and open source

## Running locally
download the page's html and open/read source locally

nomd is a static site with no build step:

    git clone https://github.com/parkecal/nomd.git
    cd nomd
    # open index.html directly, or serve it:
    python3 -m http.server

Then visit `http://localhost:8000`.

## Support

nomd is free and ad-free. If you find it useful, you can [tip me on Ko-fi](https://ko-fi.com/internetparker) to help cover the domain. No pressure — the tool stays free either way.

## License

MIT — see [LICENSE](LICENSE). © 2026 Parker Caldwell
