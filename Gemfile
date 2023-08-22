# source "https://rubygems.org"
# ruby RUBY_VERSION

# # Hello! This is where you manage which Jekyll version is used to run.
# # When you want to use a different version, change it below, save the
# # file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
# #
# #     bundle exec jekyll serve
# #
# gem 'public_suffix', '>= 3.0.3'

# # If you have any plugins, put them here!
# gem 'wdm', '>= 0.1.0' if Gem.win_platform?
# group :jekyll_plugins do
#     gem 'jekyll-feed'
#     gem 'jekyll-sitemap'
#     gem 'jekyll-paginate'
#     gem 'jekyll-seo-tag'
# end

source "https://rubygems.org"

gem "jekyll", ">= 3.8.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate", "~> 1.1.0"
  gem "jekyll-sitemap"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem "webrick", "~> 1.7"