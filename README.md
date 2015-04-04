 diff-element
============

Element that shows diffs between two texts. Built with [Polymer](https://www.polymer-project.org) and powered by  [google_diff_match_patch](https://code.google.com/p/google-diff-match-patch/).

See the [component page](http://mikaelharssjo.github.io/diff-element) for more information.

## Usage
```html
<diff-element
  first="I am the very model of a modern Major-General, I've information vegetable, animal, and mineral, I know the kings of England, and I quote the fights historical, From Marathon to Waterloo, in order categorical."
  second="I am the very model of a cartoon individual, My animation's comical, unusual, and whimsical, I know the kings of England, and I quote the fights historical, From wicked puns and stupid jokes to anvils that drop on your head.">
</diff-element>
```

![screenshot](screenshot.png)

## Contributing

Start a simple web server that ships with Python, using the commands:

```sh
python -m SimpleHTTPServer
```

Or other method using NodeJS:

```sh
http-server ./
```

This starts a web server on port 8000, so browse to `localhost:8000/test/index.html` to run the tests.

### web-component-tester

The tests are also compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). You can run them on multiple local browsers via:

```sh
npm install -g web-component-tester
wct
```
