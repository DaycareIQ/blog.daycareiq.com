Blog for DaycareIQ.com
======================

## Deployment Details ##

- Github pages `git push`
- Assets directory named `site_assets` instead of `assets` so that we can properly reverse proxy to these assets from the Rails app 
    - (rails assets dir is also `assets`)
    - Don't change this directory name without fixing reverse proxy as wel


## Instructions ##


- Add tag `featured` to add to list of featured posts
    + Top of blog index page
    + Bottom of other posts
- Add `image` to FrontMatter to get the full-width cover image
