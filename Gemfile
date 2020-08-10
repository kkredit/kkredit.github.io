source "https://rubygems.org"

gem "github-pages", ">= 207", group: :jekyll_plugins

# Theme
gem "minima", ">= 2.0"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

# Platform support

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

