source "https://rubygems.org"

gem "jekyll", "~> 4.4.1"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-sitemap', '~> 1.4'
  gem 'jekyll-redirect-from', '~> 0.16.0'
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem 'jekyll-theme-bugzilla', git: 'https://github.com/dannycolin/jekyll-theme-bugzilla', branch: 'jekyll4'

