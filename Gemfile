# frozen_string_literal: true

source "https://rubygems.org"

gem 'csv'
gem "github-pages", '~> 231', group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins
gem "jekyll-scholar", group: :jekyll_plugins
gem "webrick", "~> 1.7", group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-seo-tag'
  gem 'jekyll-redirect-from'
  gem 'jekyll-commonmark'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
