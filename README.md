# Hydejack Starter Kit

## CN Quick Start
1. add a category: register a category in _feature_categories
1. mkdir \_posts/<the_category>
1. vim \_posts/<the_category>/<the_post>
1. `bundle exec jekyll serve`
1. Open http://localhost:4000


A quicker, cleaner way to get started blogging with [Hydejack](https://qwtel.com/hydejack/).

## Quick Start
### Running locally
1. Clone repository (git users), or [download] and unzip.
2. Open terminal, `cd` into root directory (where `_config.yml` is located)
3. `bundle install` [^1]
4. `bundle exec jekyll serve`
5. Open <http://localhost:4000/hydejack-starter-kit/>

### GitHub Pages
1. Fork this repository.
2. Go to **Settings**, rename repository to `<your github username>.github.io` (without the `<` `>`)
3. Edit `_config.yml` (you can do this directly on GitHub)
    1. Change `url` to `https://<your github username>.github.io` (without the `<` `>`)
    2. Change `baseurl` to `''` (empty string)
    3. **Commit changes**.
4. Go to **Settings** again, look for **GitHub Pages**, set **Source** to **master branch**.
5. Click **Save** and wait for GitHub to set up your new blag.

## What's next?
* Open files and read the comments
* Read the [docs](https://qwtel.com/hydejack/docs/)
* Buy the [PRO version](https://qwtel.com/hydejack/download/) to get the project and resume layout, newsletter subscription box, custom forms, and more.

[^1]: Requires Bundler. Install with `gem install bundler`.

[download]: https://github.com/qwtel/hydejack-starter-kit/archive/master.zip
