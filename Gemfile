source 'https://rubygems.org'

require 'json'
require 'open-uri'

gem 'activesupport', '~>4.2.2'
gem 'yajl-ruby', '~>1.3.1'

versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']
gem 'rake'

