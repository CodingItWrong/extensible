---
title: "The Web"
---

## Extensible Web Platforms

The web is not inherently extensible because editing is not built in to its architecture. The following are some technologies built on top of the web that add some forms of extensibility.

### Wikis

Wikis are web sites with built-in editability. True wikis are often publicly available, not requiring login to view the content, and even allow edits by any user or even anonymous users. For high-profile wikis, vandalism of content is prevented by moderation and blocking of malicious users.

### IndieWeb

### GitHub Pages

This site attempts to provide an extensible architecture using the GitHub Pages platform.

The source of the site exists in a public GitHub repository. The site is generated using the Jekyll static site generator.

Extensibility on this site works as follows:

- Inspectability: the user can view the source of this site, its theme, and the Jekyll static site generator on GitHub
- Editability: if a reader wants to correct a mistake or propose an addition, there is an "Edit This Page" link on every page that takes them to the page's source in GitHub to propose an edit via pull request.
- If a user would like to make their own copy of the site, they can fork the repository. Since the site is hosted on GitHub Pages, the new repository will automatically be built and hosted as well. From there, the user can modify content and themes that GitHub Pages supports.
- If the user would like to use Jekyll features that GitHub Pages doesn't support, they can manually build the site with Jekyll and host it on any other platform.
