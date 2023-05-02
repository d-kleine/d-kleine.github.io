source "https://rubygems.org"

gem "jekyll", "~> 3.9.2"
gem "github-pages"
gem "ruby"
gem "jekyll-theme-slate"
gem "jekyll-remote-theme"

gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# kramdown v2 ships without the gfm parser by default. If you're using
# kramdown v1, comment out this line.
gem "kramdown-parser-gfm"

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.7"