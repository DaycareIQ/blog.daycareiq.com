Blog for DaycareIQ.com
======================

## Working on the Site ##

`guard`

This will start the Jekyll build, and livereload server watching for changes. LiveReload browser plugin will need to be installed/active for this to work.

## Info/Instructions ##

- (Optional) Add `category` to front-matter & URL will be `/:category/(normal-permalink)`
- Add tag `featured` to add to list of featured posts
    + Top of blog index page
    + Bottom of other posts
- Add `image` to front-matter to get the full-width cover image

## Deployment Details ##

- Github pages `git push`
- Assets directory named `site_assets` instead of `assets` so that we can properly reverse proxy to these assets from the Rails app 
    - (rails assets dir is also `assets`)
    - Don't change this directory name without fixing reverse proxy as well
