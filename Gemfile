source "https://rubygems.org"

gemspec

gem 'sqlite3', '~> 1.3.8', :platforms => :ruby

gem 'pry'

# Hinting at development dependencies
# Prevents bundler from taking a long-time to resolve
group :development, :test do
  gem 'mime-types', '3.1'
  gem 'builder'
  gem 'rubocop', require: false
end
