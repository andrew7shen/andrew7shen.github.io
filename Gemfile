source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# NOTE: This Gemfile is for LOCAL PREVIEW ONLY. The live site is built by
# GitHub Pages, which ignores this file and uses its own pinned toolchain.
#
# We pin Jekyll 3.9 (the version GitHub Pages builds with) rather than using
# the `github-pages` meta-gem, because that gem hard-pins liquid 4.0.3, which
# calls String#tainted? -- removed in Ruby 3.2+ and so unusable on modern Ruby.
# liquid 4.0.4 drops that call and is compatible with Jekyll 3.9.
gem "jekyll", "~> 3.9.5"
gem "liquid", "~> 4.0.4"

# GitHub Flavored Markdown parser (kramdown-parser-gfm), as _config.yml selects
gem "kramdown-parser-gfm"

# Gems that left Ruby's default set in 3.4/4.0 but are still required by
# Jekyll 3.9 and its dependencies.
gem "csv"
gem "bigdecimal"
gem "base64"
gem "logger"
gem "ostruct"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Plugins enabled in _config.yml
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-redirect-from"
  gem "jemoji"
  gem "webrick", "~> 1.8"
end
