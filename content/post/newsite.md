+++
categories = []
date = "2015-07-18T02:51:55+01:00"
description = ""
keywords = []
title = "New Site"

+++

So, I finally got round to setting up a proper website for myself. I toyed with the idea of writing something from scratch for a while using something like [bootstrap](http://getbootstrap.com) or [skeleton](http://getskeleton.com) until I was introduced to [`hugo`](http://gohugo.io), a wonderfully simple static site generator.

In it's most basic form, a static site generator takes content in some kind of markup language, applies a theme, and renders the content to HTML. You can then drop this HTML on a lightweight webserver (I use thttpd) for a very low-footprint website. Static site generators combine the ease of using a CMS with the speed and efficiency of pure static HTML. I chose `hugo` in particular due to it's super short build times, support of Markdown and it's built-in webserver.

Having now used `hugo` for a few days to set up this site, I can say I'm 100% on board with the whole concept. I know Markdown pretty much inside out which makes writing new content a breeze and using static HTML as opposed to a dynamic CMS does wonders for both [security](https://wpvulndb.com) and page load times. I haven't tested it yet, but I should hopefully be able to setup hugo in a git recieve hook, so that all I need to do in order to update the site is run a `git push` from my `~/src/alfiepates.me` directory and have the server automatically build the new website. Expect more blog posts about it in the future, as I figure it out.

In conclusion? Hugo is fucking awesome, you should totally check it out next time you need a static site for a project.

*Note that the current (as of 18-07-2015) homebrew formula for `hugo` isn't the latest version, and doesn't support a lot of themes. In the mean time, grab the [binary](https://github.com/spf13/hugo/releases) and chuck it in your `/usr/local/bin`.*
