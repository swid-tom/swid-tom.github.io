# Tomasz's site

Hey, this is the code behind my personal website:
[swid-tom.github.io](https://swid-tom.github.io/).

It's a simple one-page site, hosted with GitHub Pages and built with Jekyll.

## Making changes

- Most of the text and site details live in [`_data/settings.yml`](_data/settings.yml).
- The homepage sections are listed in [`index.html`](index.html).
- Styles live in [`assets/scss/`](assets/scss/).
- Local Jekyll build files are ignored by Git, so they won't clutter the repo.

## Previewing locally

You'll need Ruby and Bundler. From the project folder, run:

```sh
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).
Jekyll rebuilds the preview as you edit files; refresh the page to see updates.

## Publishing

The public site updates after you commit and push your changes to GitHub. Local
preview changes are not published automatically.

## Credits

This site started with the [Kross Jekyll theme by Themefisher](https://github.com/themefisher/kross-jekyll), then got customized for my own use. The theme's MIT license is in [`LICENSE`](LICENSE).
