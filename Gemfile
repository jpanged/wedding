source "https://rubygems.org"

# Jekyll 4.x (modern) instead of the github-pages monolith.
gem "jekyll", "~> 4.3"

# Theme (gem-based; replaces `remote_theme: mmistakes/minimal-mistakes`).
# Pinned to 4.19 to match the layouts/includes vendored in this repo
# (later 4.2x releases removed includes like browser-upgrade.html).
gem "minimal-mistakes-jekyll", "~> 4.19.0"

gem "tzinfo-data"
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Formerly part of the Ruby standard library, no longer default gems on
# Ruby 3.4+. Jekyll and its deps still require these.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "webrick"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
end
