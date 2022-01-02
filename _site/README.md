# Test site for Neural concepts

To develop this site locally:

[Install `rbenv`](https://github.com/rbenv/rbenv). With `rbenv` installed, activate Ruby 2.6.9 using:

```
rbenv install 2.6.9
rbenv global 2.6.9
```

Create a fork of this repo. Locally clone the repo.

`cd` into the local copy of this repo, use `gem install` to install the missing packages (similar to `pip install -r requirements.txt`).

Use `bundle exec jekyll serve` to run test server.

## Add a new post

To add a new visualization to the mix, add a new Markdown file to `_posts`. Use the other posts as reference. Different types of content are acceptable:

- image + external link
- movies: you can use youtube or gifs. Fill the `video` or `gif` property to make this work.
- iframe: can be used to embed different kinds of javascript visualizations. Use the `iframe` property to make this work. Your iframe should scale appropriately with different embedding sizes. Fill in `iframeAspectRatio` (for example, 1.78 for an iframe in the 16:9 aspect ratio). Note that you can only use `https` iframes, NOT `http`.

Add preview images to `assets/images`. Make the preview image at least 1010 pixels wide.

Commit changes remotely and open a PR to allow us to pull in your changes.

## Credits

This demo uses "Pintereso" - [Jekyll Template by WowThemes.net](https://github.com/wowthemesnet/template-pintereso-bootstrap-jekyll).
