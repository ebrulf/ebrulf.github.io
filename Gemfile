source "https://rubygems.org"
# Hejka! Tutaj zarządzasz uruchamianą wersją Jekylla.
# Jeśli chcesz użyć innej wersji, zmień ją poniżej, zapisz
# plik i uruchom komendę `bundle install`. Uruchom Jekylla poprzez `bundle exec`, w ten sposób:
#
#     bundle exec jekyll serve
#
# To pomoże zapewnić, że właściwa wersja Jekylla obecnie działa.
# Miłego Jekyllowania!
# gem "jekyll", "~> 4.3.2"
# To jest domyślna skórka dla nowych stron Jekylla. Możesz ją zmienić, jak ci się podoba.
gem "jekyll-theme-tactile", "~> 0.2.0"
# Jeśli chcesz korzystać z GitHub Pages, usuń linijkę "gem "jekyll"" powyżej
# i odkomentuj poniższą. Abu zaktualizować, uruchom `bundle update github-pages`.
gem "github-pages", '~> 232', group: :jekyll_plugins
# Jeśli masz jakieś dodatkowe pluginy, dodaj je tutaj!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap", "~> 1.4.0"
end

# Windows i JRuby nie dostarczają plików zoneinfo, więc dołącz klejnot tzinfo-data
# wraz z powiązaną biblioteką.
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Szybsz pilnowanie katalogów na Windowsie
gem "wdm", "~> 0.2.0", :platforms => [:windows]

# Zablokuj klejnot `http_parser.rb` do wersji `v0.6.x` na JRuby, bo nowsze jego wersje
# nie mają odpowiedników w Javie.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.8"
gem "fiddle"
gem 'faraday-retry', "~> 2.2.0"
