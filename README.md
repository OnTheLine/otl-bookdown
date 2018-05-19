---
title: "About"
permalink: /
last_modified_at: 2018-05-18T16:28:04-05:00
---
In this Jekyll-book repo, the README.md page also serves as the Introduction>About page (but it also could serve as the Introduction page, separate from About)

Goal:
- create a static site for book-length content, composed in multiple Markdown page files
- navigate pages with two-level sidebar (ideally, a self-collapsing sidebar, displaying only current section)
- support embedded content: dynamic iframes, YouTube/Vimeo, etc.
- publish with GitHub Pages using web interface or GitHub Desktop (not command line) to simplify process for new authors

Current solution:
- Publish Markdown text with GitHub Pages and Jekyll remote_theme Minimal Mistakes https://mmistakes.github.io/minimal-mistakes
- Simple GitHub web interface or GitHub Desktop. No command-line necessary (so far)

Create your own:
- fork a copy of the current repo
- learn how GitHub Pages supports remote_theme https://github.com/blog/2464-use-any-theme-with-github-pages
  - this repo is dependent on the Minimal Mistakes theme https://github.com/mmistakes/minimal-mistakes
- change _config.yml settings in your forked repo to match your needs
- compose Markdown files, set front matter at top, and upload to _pages folder in your forked repo
  - Note that this demo uses README.md as the home page, rather than index.html. See https://jekyllrb.com/docs/pages/#homepage
- change _data/navigation.yml to display in sidebar in your forked repo
- publish your forked repo with GitHub Pages using Settings > Publish > Master branch
  - option 1: to publish as a Personal or Organizational site (eg: https://action-lab.github.io), then use this same github.io address as your repo name
  - option 2: to publish as a repository Project site (eg: https://action-lab.github.io/book), then your repo name is appended at the end of your github.io address
  - option 3: see also CNAME settings to use your own URL
- Reminder: when pushing new content, allow up to 1 minute for GitHub Pages to rebuild, and do a hard-refresh of all pages to make sure you're seeing newly-built content.

Credits:
- Minimal Mistakes Jekyll theme by Michael Rose https://github.com/mmistakes/minimal-mistakes

To Do:
- decide if my simple GitHub Pages remote theme installation (without bundler) works as well as the author's recommended GitHub Pages installation https://github.com/mmistakes/minimal-mistakes#installation
  - I do not understand or see need for the "replace gem" step as author describes
- the autolink problem: my goal is for simple links to be converted automatically to hyperlinks. I need this feature to work for endnotes with hyperlinks. Why does autolink work in GitHub-flavored Markdown, but not in Minimal Mistakes? Is this due to kramdown generator?
  - Try kramdown syntax: insert angle brackets, like this:  <https://kramdown.gettalong.org/syntax.html#links-and-images>
  - See autolink in Redcarpet Markdown parser https://github.com/vmg/redcarpet
  - See this reference to an autolink extension https://jekyllrb.com/docs/configuration/#markdown-options
  - see this Jekyll Ruby autolink plugin https://github.com/vmg/rinku
- Is Jekyll Kramdown HTML converter the best solution? Any alternatives to consider?
- learn how to display home page
- learn how to configure splash pages
- learn how to create internal page links, download files https://jekyllrb.com/docs/posts/#including-images-and-resources,  - see example: Be sure to enable pagination if using the [`home` layout]({{ "/docs/layouts/#home-page" | absolute_url }})
  - see also this note about accessing static files https://jekyllrb.com/docs/static-files/
- learn how to configure search_full_content https://mmistakes.github.io/minimal-mistakes/docs/configuration/
  - see also https://github.com/mmistakes/minimal-mistakes/issues/1409
- learn how to modify footer script to show CC licensing and other text and links (how to cite book) https://mmistakes.github.io/minimal-mistakes/docs/javascript/
- determine which files to customize and host in my repo https://mmistakes.github.io/minimal-mistakes/docs/overriding-theme-defaults/
- display date below the page title https://github.com/mmistakes/minimal-mistakes/issues/1428
- display co-authors (fancy in sidebar, or simply byline text)
- learn how to set up Google Analytics https://mmistakes.github.io/minimal-mistakes/docs/configuration/
- decide if each book (of pages) also needs blog (of posts) https://mmistakes.github.io/minimal-mistakes/docs/layouts/
- make sure that default feed URL is sufficient https://mmistakes.github.io/minimal-mistakes/docs/configuration/
- learn how to insert a Gallery of images https://mmistakes.github.io/minimal-mistakes/docs/helpers/
- decide about Redcarpet extension SmartyPants to turn on smart quotes and em-dash conversion https://jekyllrb.com/docs/configuration/#markdown-options
- ensure that Chicago-style endnotes work well with each section
- automate export or compile settings from Scrivener to MultiMarkdown (and confirm that all works with GitHub Pages markdown processor)
- Any way to add bibliography file? See https://minicomp.github.io/ed/documentation/#bibliographies and https://github.com/inukshuk/jekyll-scholar (which CANNOT be hosted with default GitHub Pages workflow)
