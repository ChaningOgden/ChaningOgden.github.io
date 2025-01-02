# My Blog

Depends on:

* [Jekyll](https://jekyllrb.com/) static site generator
* [github pages](https://pages.github.com/)

## Using Jekyll

### Deploying Jekyll Blog

With [GitHub Pages deploys](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site), you either need to enable GitHub Actions to execute the Jekyll build, or you need a ```.nojekll``` file in the root of the source branch so it bypasses the process and deploys the content directly.

### Theming Jekyll Blog

You can [add themes](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll), with many responsive layout options out there. One example is [Minimalist Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

### Styling

[Kramdown](https://jekyllrb.com/docs/configuration/markdown/) is the default markdown processor, and follows the [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

## Tips

#### Auto refresh page with each change

```bundle exec jekyll serve --livereload``` 

#### Codespace Development

The universal default image comes with all the needed parts to get rolling right away.



