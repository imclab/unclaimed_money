source 'https://rubygems.org'

gem 'rails', '3.2.13'

gem 'capybara'
gem "capybara-webkit"
gem 'json', '1.7.7'
gem 'haml-rails'
gem 'httparty'
gem 'jquery-rails'
gem 'nokogiri'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'compass-rails' # you need this or you get an err
  gem 'zurb-foundation', '~> 4.0.0'
end

group :development, :test do
  gem 'awesome_print'
  gem "brakeman", :require => false
  gem 'faker'
  gem 'factory_girl_rails'
  gem 'guard'
  gem 'guard-rspec'
  gem 'mocha', require: 'mocha/api'
  gem 'net-http-spy'
  gem "parallel_tests"
  gem 'pry'
  gem 'pry-nav'
  gem 'rspec-rails'
  gem "zeus-parallel_tests"
end

group :development do
  gem "better_errors"
  gem "binding_of_caller"
  gem 'guard-livereload'
  gem 'hpricot'
  gem 'meta_request'
  gem 'mysql2'
  gem 'quiet_assets'
  gem 'ruby_parser'
  gem 'thin'
end

group :production do
  gem 'pg'
end

group :test do
  gem 'database_cleaner'
  gem 'launchy'
  gem 'shoulda'
  gem 'simplecov', :require => false
  gem 'webmock'
end