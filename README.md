# artsy hugo page

A page primarily meant for use as an art portfolio. Since I'm not planning to release this for further use, no theme is being used for now.

## run for dev

- `hugo server -D` will run a dev-server that refreshes, when relevant files have changed. Remove the `-D` if no draft posts or pages should be shown.

## deploy

- `hugo` creates a `public` folder. The contents of which can be uploaded to a static file host.

## create new content

- `hugo new gallery` for new gallery content - creates a full new subfolder including images etc.
- `hugo new product.md` for new product content - creates only the new markdown file
