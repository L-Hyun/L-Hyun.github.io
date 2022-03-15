source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.2.1" #previous: 4.1

gem "jekyll-theme-hydejack", "~> 9.1.6"

# IMPORTANT: The followign gem is used to compile math formulas to
# KaTeX during site building.
#
# There are a couple of things to know about this gem:
# *  It is not supported on GitHub Pages.
#    You have to build the site on your machine before uploading to GitHub,
#    or use a more permissive cloud building tool such as Netlify.
# *  You need some kind of JavaScript runtime on your machine.
#    Usually installing NodeJS will suffice.
#    For details, see <https://github.com/kramdown/math-katex#documentation>
#
# If you're using the MathJax math engine instead, free to remove the line below:

group :jekyll_plugins do
  gem "jekyll-default-layout", git: "https://github.com/benbalter/jekyll-default-layout"
  gem "jekyll-feed"
  gem "kramdown-math-katex"
  gem "jekyll-optional-front-matter"
  gem "jekyll-paginate"
  gem "jekyll-readme-index"
  gem "jekyll-redirect-from"
  gem "jekyll-relative-links"
  gem "jekyll-seo-tag", git: "https://github.com/hydecorp/jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-titles-from-headings"
  gem "jekyll-avatar"
  # Non-Github Pages plugins:
  gem "jekyll-last-modified-at"
  gem "jekyll-compose"
  gem "kramdown-parser-gfm"
end

gem 'wdm' if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?
gem "webrick", "~> 1.7"