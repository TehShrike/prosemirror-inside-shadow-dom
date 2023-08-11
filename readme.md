# Prosemirror issues inside a shadow dom

To reproduce locally:

```sh
npm it
```

and then open http://localhost:8080

**or**

visit https://tehshrike.github.io/prosemirror-inside-shadow-dom/

# Expected behavior

The editor inside the shadow dom should behave the way that the one outside the shadow dom does.

# Observed behavior in the shadow dom version

In Firefox and Chrome, the icons in the buttons in the menu bar are not visible.

In Chrome, the editor container box is really large.

In Firefox, attempting to select text with Cmd+shift+left/right does not do anything.