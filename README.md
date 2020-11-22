# SASE 2020-2021 Mentorship Program Profiles

Built with:
- Jekyll
- [Jekyll Onassis Theme](https://github.com/ohduran/Onassis)

## Useful Links
- [Jekyll Docs](https://jekyllrb.com/docs/)

## How to edit
Mentor and mentee profiles are stored in .md files under the `/collections` folder. Each file is rendered onto a template under `_layouts/post.html`

The entire website is built upon the html templates found in `_layouts` and `_includes`. To move content around, edit the HTML tags in those folders and rebuild the site.

## Deploying
1. `git checkout` the repo locally
* make sure you have Ruby and Jekyll requirements installed (instructions below)
2. run `bundle exec jekyll build`
3. `git push` repo to master and check `https://sase-drexel.github.io/mentorship-profiles/` is updated with new profiles

## Viewing Locally

1. follow instructions on [install Jekyll locally](https://jekyllrb.com/docs/installation/)
2. `git clone` this repo
2a. run `gem install bundler` if you do not already have bundler installed
3. run `bundle install` to install repo dependencies
4. run `bundle exec jekyll serve` -- by default the site will be built into a new folder `_docs` and hosted on `localhost:4000`
