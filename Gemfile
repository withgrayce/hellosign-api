source 'https://rubygems.org'

# Specify your gem's dependencies in hellosign-api.gemspec
gemspec

group :development, :spec do
  gem 'pry'
  gem 'growl' if `uname` =~ /Darwin/
  gem 'guard'
  gem 'guard-bundler'
  gem 'guard-rspec'
  gem 'coveralls', :require => false
end
