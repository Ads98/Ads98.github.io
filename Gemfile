source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
#gem "jekyll", "~> 4.4.1"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "jekyll", "~> 4.2"
gem "jekyll-scholar"

gem "minima", "~> 2.5"
gem "sass-embedded", "~> 1.56.0"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.

#gem "github-pages", "~> 232", group: :jekyll_plugins


# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'classifier-reborn'
    gem 'jekyll-archives'
    gem 'jekyll-email-protect'
    gem 'jekyll-get-json'
    gem 'jekyll-imagemagick'
    gem 'jekyll-jupyter-notebook'
    gem 'jekyll-link-attributes'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-regex-replace'
    gem 'jekyll-sitemap'
    gem 'jekyll-tabs'
    gem 'jekyll-toc'
   # gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    gem 'unicode_utils'
    gem 'webrick'

end

group :other_plugins do
  gem 'css_parser'
  gem 'feedjira'
  gem 'httparty'
  gem 'activesupport'

end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gemS
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]



