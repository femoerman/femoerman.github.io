# frozen_string_literal: true

source "https://rubygems.org"

# gem "rails"
gem "jekyll"
#gem "webrick", "~> 1.8"
gem "jekyll-remote-theme"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

group :jekyll_plugins do
  gem 'jekyll-sitemap'
  gem 'jekyll-feed'
  gem 'jekyll-seo-tag'
end