# Co-op Digital Engineering blog

Built using a fork of **Jekyll Now** (https://github.com/barryclark/jekyll-now/)

## Quick Start
There are 3 different ways that you can make changes to your blog's files:
1. Edit files within your new username.github.io repository in the browser at GitHub.com (shown below).
2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
3. Clone down your repository and make updates locally, then push them to your GitHub repository.

## Publishing first blog post
This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

1. Go to `/_posts/` and create a new file:
2. filename is in this format: year-month-day-title.md
3. Include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post

## Adding a new page
1. Any page in root with a .md or .html
2. To add to the navigation edit `/_layouts/default.html`

## Configuring
Check out `_config.yml` for some of the settings.

## Local Development
1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
