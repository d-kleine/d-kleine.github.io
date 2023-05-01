source "https://rubygems.org"

gem "jekyll"
gem "github-pages"
gem "ruby"
gem "jekyll-theme-slate"
gem "jekyll-remote-theme"

gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
