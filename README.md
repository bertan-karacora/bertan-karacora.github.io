
# bertan.karacora.github.io

This repository holds the code for my personal website hosted by [GitHub Pages](https://pages.github.com). This repository is built on the [Jekyll](https://jekyllrb.com) theme [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy).

## Getting Started

1. Set site-wide configuration and add your content.
2. Upload any files (like PDFs, .zip files, etc.) to the `assets/files/` directory. They will appear at https://[your GitHub username].github.io/files/[filename].  
3. Check status by going to the repository settings, in the "GitHub Pages" section

## Running Locally

When you are initially working your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:

1. Initialize the repository.
2. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-full ruby-bundler nodejs npm`
3. Run `npm i && npm run build`
4. Run `bundle config set --local path 'vendor/bundle'; bundle` to install ruby dependencies.
5. Run `bundle exec jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
