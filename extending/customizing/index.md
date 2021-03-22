---
title: Customizing
---

If you've made your own copy of this site, you can make further customizations. Some can be made while hosting the site on GitHub Pages, and others require you to host the site somewhere else.

On GitHub Pages you can:

- [Change the theme](https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll) of the site to one of a dozen or so supported themes
- Add a [custom domain name](https://docs.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site)

If you'd like to make any of the following changes, you can use your same site code but you'll need to host the site somewhere other than GitHub Pages:

* Change the theme of the site to another custom Jekyll theme
* Add additional Jekyll plugins
* Store your site in a version control system other than GitHub

To do this, you'll need to decide where to host your Jekyll site. You have a few options:

- A platform like [Netlify](https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/#main) that automatically runs the build for you.
- Any web host that allows you to upload HTML files, in which case you'll need to run the Jekyll build locally

In the latter case, you'll want to be set up to run Jekyll locally. To do this:

- [Clone your repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) to your computer
- [Install Jekyll](https://jekyllrb.com/docs/installation/)
- Run `jekyll serve` to run the web site locally
- Run `jekyll build` to build the web site to the `_site` folder
- Upload the contents of the `_site` folder to your web host
- Don't forget to commit any changes you make to git and push them up to GitHub or your preferred version control service
