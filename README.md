# acps-sei.github.io Website

This is the master repository for the [ACPS-SEI website](https://acps-sei.github.io).

It builds on the Jekyll static website builder
and GitHub pages, see [Github Pages and Jekyll](https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll) for details.

To setup
- git clone
- bundle exec jekyll build

To test
- bundle exec jekyll serve

The site is organized as follows

- in `news`, short blog messages to announce new stuff: papers, tools, etc
- in `_includes/footer.html`, the upper menu
  - for each item in the menu, a corresponding `.html` or `.md` page should be at the root of the site

# Markdown resources

* Markdown cheatsheet: https://www.markdownguide.org/cheat-sheet/

* In a `.md` file, the first cartouche indicates which layout to use from `_layout` directory

* To regenerate the list of publications, run `generate_publis.sh`, see script for installing dependencies.