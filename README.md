# orbi-demo

A tiny todo app for trying [Orbi](https://orbi.build/?ref=gh-orbi-demo) before you point it at your own project. Orbi can change anything here without touching your real code.

Open `index.html` in a browser to use it. The list logic lives in `src/todo.js` and is tested in `test/`; CI runs the tests on every pull request.

## Try it

1. Connect this repository on the Orbi Cloud status page.
2. Open an Issue that asks for one small change, for example:
   - Add a "Clear completed" button.
   - Show how many todos are left.
   - Keep the list after a page reload.
   - Let me edit a todo's title by double-clicking it.
3. Add the `ai-ready` label to the Issue.

Orbi writes the change, an independent reviewer checks it, and only the reviewed commit is merged. Open `index.html` again to see it. When you are ready, ask Orbi for a release and it tags one.

## Run the tests

```
npm test
```

Requires Node.js 20 or later. No dependencies.

## License

MIT
