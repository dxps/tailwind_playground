# The Basics

These basics - included in `basics.html` file means:

- Spacing (with Margin and Padding)
- Box Properties
- Sizing and Numbering
- Typography
- Colors
- Pseudo Classes



<br/>

## Usage

To open these HTML files in a browser just one of the options described below.

like any other page (using `http://` scheme instead of `file://`), 

One of the simplest ways is to use your local Python installation. This means:
- if `python -V` works and reports some 2.x.y version, then use `python -m SimpleHTTPServer` while being in this directory.
- else if `python3 -V` works and reports some 3.x.y version, then use `python3 -m http.server` while being in this directory.

Another popular alternative is to the [http-server](https://www.npmjs.com/package/http-server) NPM package. This means:
- have it installed globally by running `npm install -g http-server`
- and run `http-server . -p 8000` while being in this directory (`-p 8000` is optional, if you want a specific listening port)

If you use VS Code, then [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) is a great extension for this purpose.

<br/>

