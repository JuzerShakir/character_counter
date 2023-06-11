Using `character-counter` from stimulus library.

Commands I ran to make `character-counter` work with a form field:

```
- rails new -j esbuild -c bootstrap
```

```
- bundle add simple_form
```

- rails g simple_form:install --bootstrap

```

```

- rails g scaffold Post title description:text

```

```

- yarn add stimulus-character-counter

```

- Register the character-counter controller in `index.js` file.
- Look at `_form.html.erb` file to see how to bind the field and show the counter.
```
