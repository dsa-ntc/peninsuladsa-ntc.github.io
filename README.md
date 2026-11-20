# Peninsula DSA Website

This repo is based on the default template provided by the DSA CTC, with some modifications. It uses Jekyll and the [Lone Wolf Theme](https://github.com/manid2/lone-wolf-theme), like the original template provided by the DSA CTC.

The website is currently hosted with Github Pages on https://peninsuladsa.org.

For any questions or feedback, please contact the Comms Committee.

## Repo structure (website content)

- `_data` contains data that is often reused in templates throughout the site. Updating stuff here might affect multiple pages
  - `blog.yml` contains social media links (TODO?)
  - `books.yml` contains info on the books we are going through in our reading group. This feeds into the reading group page on the website.
  - `copy.yml` contains an about and welcome message included in every page
  - `nav.yml` contains links on the nav bar (top bar)
- `_pages` contains informational pages such as about pages, information for joining the chapter, etc. If you add stuff here, it probably also belongs in the nav bar.
- `_posts` contains posts (usually public statements). Create files here to make new posts. In general, if it's a one-off, it's a post. If it's information that is about us in general, it's a page.
- `assets` contains static assets (images, files, etc) that can be linked to in other pages. Try not to put very large files here (TODO: we may want to switch to LFS to not clobber git with a lot of binary blobs).

## Changes compared to the default template

The original template provided by CTC was a fork of the upstream Lone Wolf Theme, with some minor modifications. This makes it somewhat difficult to figure out what code belongs to the upstream theme and which are overrides specific to us. The repo has been refactored to include the upstream theme as a remote theme, with a minimal set of overrides custom to us.

If we have a file in this repo with the same name and path as the [upstream repo](https://github.com/manid2/lone-wolf-theme), our overrides will take precedence. This is a way to modify things in the theme that we want to change but they do not offer an option for us to change it easily. However, we should try to keep custom patches to a minimum, to avoid having to maintain a bunch of extra stuff. If you see things in this repo referencing files that are not present, it is likely in the upstream repo.

## Repo structure (technical)

In addition to the website content mentioned above, there is also:
- `_layouts`: common templates that apply to different page types (e.g. posts can be formatted in one way, the home page might be a different way, etc). Content is usually wrapped in one of these layouts. Remember to check the upstream theme for layouts that we aren't duplicating here.
- `_includes`: snippets of HTML or markdown that is included in posts or layouts. Headers, footers, helper scripts, etc. If it's worth reusing in a couple of places, it likely belongs here. Remember to check the upstream theme for includes that we aren't duplicating here.
- `_sass`: This directory contains stuff relevant for CSS. The main Sass file (basically a superset of CSS that allows more features, and eventually compiles into CSS) we have is in `assets/css/main.scss`, and it includes files in this directory. Remember to check the upstream theme for Sass files that we aren't duplicating here.
- `_config.yml`: main Jekyll config, contains some important site metadata
- `Gemfile`, `Gemfile.lock`, `CNAME`, `.bundle`, `.gitignore`: Don't touch unless you know what you're doing

## Local testing

This section is for people who are technically minded (can run some commands on their system), and are looking to make modifications to the site's templates or similar. If you are just updating posts, feel free to just make a PR (pull request) with your change, and updating markdown text should be fairly easy. (TODO: we may implement some sort of CI so people can preview their changes whenever they make a pull request with their change)

To test out changes to the website, follow the following steps:
- Install `bundler` to install relevant ruby packages and run Jekyll.
- Install relevant dependencies (you only need to do this once): `bundle install`
- To generate the site once: `bundle exec jekyll build`. This will place output in the `_site` directory
- To start a local webserver that serves the site so you can iterate on changes: `bundle exec jekyll serve` and open the result in your browser. Remember to do a full refresh (`Shift+F5`) if you are making changes to things like CSS, which might be cached by the browser
