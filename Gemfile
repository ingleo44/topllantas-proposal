source "https://rubygems.org"

# Jekyll version
gem "jekyll", "~> 4.3.0"

# Tema por defecto de GitHub Pages
gem "minima", "~> 2.5"

# Plugin de GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Plugins de Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-relative-links"
  gem "jekyll-optional-front-matter"
  gem "jekyll-readme-index"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
end

# Windows y JRuby no incluyen zoneinfo files, necesario agregar tzinfo-data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster para watching directories en Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# kramdown v2 ships without the gfm parser by default
gem "kramdown-parser-gfm"

# Lock Jekyll to 4.3.x
gem "jekyll", "~> 4.3.0"
