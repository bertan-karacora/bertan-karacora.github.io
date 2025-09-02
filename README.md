
# bertan.karacora.github.io

This repository is built upon [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## Getting Started

1. Set site-wide configuration and add your content.
2. Upload any files (like PDFs, .zip files, etc.) to the `files/` directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
3. Check status by going to the repository settings, in the "GitHub pages" section

See more info at https://academicpages.github.io/

## Running Locally

When you are initially working your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:

1. Clone the repository and made updates as detailed above.
2. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
3. Run `bundle config set --local path 'vendor/bundle'; bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
4. Run `bundle exec jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
