# Readme

## Build on Linux

```bash
bundle config set --local path 'vendor/bundle'
```

sets the path where ruby gems are installed for the project only.

```bash
bundle install
```

installs dependencies.

```bash
bundle exec jekyll serve --watch
```

runs a local server and watches changes.
You should see the site on http://localhost:4000/blog/
