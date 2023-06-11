Using `character-counter` from stimulus library.

Commands I ran to make `character-counter` work with a form field:

```bash
rails new -j esbuild -c bootstrap
```

```bash
bundle add simple_form
```

```bash
rails g simple_form:install --bootstrap
```

```bash
rails g scaffold Post title description:text
```

```bash
yarn add stimulus-character-counter
```

- Register the character-counter controller in `index.js` file.
- Look at `_form.html.erb` file to see how to bind the field and show the counter.
