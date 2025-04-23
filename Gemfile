source "https://rubygems.org"

# Comment out the Jekyll version since github-pages will manage it
# gem "jekyll", "~> 4.4.1"

# Add github-pages gem which will bring in the correct Jekyll version
gem "github-pages", "~> 232", group: :jekyll_plugins

# Remote theme plugin
gem "jekyll-remote-theme"

gem "jekyll-paginate"

# Include cache plugin for performance
gem "jekyll-include-cache", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
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

# Explicitly add webrick as it's no longer bundled with Ruby 3.0+
gem "webrick", "~> 1.8"