# Add RubyGems source location for Bundler.
source "https://rubygems.org"

# Not sure.
ruby RUBY_VERSION

# Bundle `tzinfo-data` gem for timezone interoperability.
gem 'tzinfo-data', platforms: [ :mingw, :mswin, :x64_mingw, :jruby ]

# Jekyll uses the gem "listen" to track changes. There is built-in support for
# UNIX systems, but requires an extra gem for compatibility with Windows.
gem 'wdm', '~> 0.1.0' if Gem.win_platform?

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
#gem "jekyll", "3.3.1"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed", ">=0.8.0"
end
