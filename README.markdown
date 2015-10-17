Editing the site
================

Wherever possible, [Markdown](https://daringfireball.net/projects/markdown/) is used to facilitate easy edits.

Generally, in each folder, there will be either an `index.markdown` or `index.html`. So to change what's on https://www.bergems.org/officers/, you'd edit `/officers/index.markdown`.

There are also a couple of things that have been extracted for easier editing, so that you don't need to dig too far into the code.

The contents of `_includes/news.markdown` will be inserted onto the home page. This is the preferred means of adding new content.

You can update the number of EMTs / training corps members across the entire site by changing the values in `_data/membership.yml`.

Add new CPR sessions to `_data/cpr.yml` to be displayed on <https://www.bergems.org/learn-cpr/>. There are some comments in that file that will give you more guidance.

If you need to include new images, upload them to the `./assets/images` folder.

More complicated changes
========================

If you need to make more complicated changes, you'll probably need to look into [Jekyll](http://jekyllrb.com/), the templating engine, [Bootstrap](http://getbootstrap.com/), and good old HTML.

Our CSS customizations are written in [SCSS](http://sass-lang.com/) and stored in `./assets/stylesheets/mcsms.scss`.
