source "https://rubygems.org"

# GitHub Pagesの標準に近い構成にします
gem "jekyll", "~> 4.4"

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-remote-theme"
end

# 依存関係エラーを避けるため、これらを追加・整理します
gem "webrick", "~> 1.8"
gem "tzinfo-data"
gem "google-protobuf", "~> 3.25" # sass-embeddedとの競合回避のため