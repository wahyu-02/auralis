source "https://rubygems.org"

# Gunakan GitHub Pages gem untuk kompatibilitas
gem "github-pages", group: :jekyll_plugins

# Jika Anda ingin plugin tambahan, tambahkan di bawah ini
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12" # Contoh plugin Jekyll
end

# Windows dan JRuby tidak menyertakan file zona waktu, jadi tambahkan gem ini.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster untuk memantau direktori pada Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem untuk JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
