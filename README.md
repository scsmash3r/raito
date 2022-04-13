<img src="logo.svg" width="100%" style="margin: auto;"/>

# [Raito](https://arnaud.at/raito) | Mini Markdown CMS ✨📝
> Build your website with a single file!

Raito is an ultralight static CMS/Wiki that weights 8kb.  
Hence the name, ライト meaning *light* in Japanese.

Made by [Arnaud de Saint Meloir](arnaud.at), inspired by the defunct [MDwiki](https://github.com/Dynalon/mdwiki/)

Check the [Demo 🔥](https://arnaud.at/raito)

## Install
Just drop `index.html` in your website root.

## Usage
Place Markdown files in the directory. Folders redirect to `README.md`. 

Most modern Markdown components are supported, check [the examples](https://arnaud.at/raito/#/examples).


### Relative links
All links to local markdown files should be relative (not starting with `/`).  
Directory links (ending with `/`) will display the root `README.md`.

### Customisation
Edit the `config` variable in `index.html`.

### Subdirectory install
To install Raito in a subdirectory, just specify the folder relative to root in `config.root` in `index.html`.
Check out the branch `subdir-example` for a working example at [http://localhost:8000/subdir_example/](http://localhost:8000/subdir_example/)

### Syntax Highlighting
Uncomment the  [highlight.js](https://github.com/highlightjs/highlight.js/) imports in `index.html`.
This adds significant bundle size.

### Components
Components are visible in every page, and useful for navbars, sidebars and footers.

Create your component in a `.md` file, then add it to `config.json`.

### Chart.js
`Chart.js` support is not official yet, but check out this [setup example](https://github.com/arnaudsm/raito/tree/chartjs-example).

## Development
### Run locally
Run a local HTTP server, and access http://localhost:8000 

```bash
docker-compose up
# OR
python -m http.server 8000
```

### Dependencies
- [Marked.js](https://github.com/markedjs/marked/)
- [highlight.js](https://github.com/highlightjs/highlight.js/) (Optional)

### Todolist
- [x] Subdir Support
- [x] Dark mode
- [x] Fix history navigation
