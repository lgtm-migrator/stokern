# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby '3.1.2'

gem 'rails', '~> 7.0', '>= 7.0.4'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap', '>= 5.2.2'
gem 'bootswatch'
gem 'coffee-rails', '~> 5.0', '>= 5.0.0'
gem 'devise', '>= 4.8.1'
gem 'dotenv', '>= 2.8.1'
gem 'high_voltage'
gem 'it', '>= 2.0.0'
gem 'jbuilder', '~> 2.11', '>= 2.11.5'
gem 'jquery-rails', '>= 4.5.0'
# gem 'libv8-node', '~> 16.10.0.0'
gem 'mini_racer', '~> 0.6.3', platforms: :ruby
gem 'nokogiri', '>= 1.13.9'
gem 'pg'
gem 'puma', '>= 5.6.4'
gem 'rack-timeout'
gem 'rails-ujs', '>= 0.1.0'
gem 'sass-rails', '>= 6.0.0'
gem 'turbolinks', '~> 5'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
gem 'uglifier', '>= 1.3.0'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'brakeman' # , '< 4.5.1'
  gem 'guard-brakeman'
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'guard-rubocop', '>= 1.4.0'
  gem 'listen'
  gem 'rails-erd', git: 'https://github.com/voormedia/rails-erd'
  gem 'rails_layout'
  gem 'rb-fchange', require: false
  gem 'rb-fsevent', require: false
  gem 'rb-inotify', require: false
  gem 'rubocop', '>= 1.25.1', require: false
  gem 'rubocop-performance', '>= 1.10.1'
  gem 'rubocop-rails', '>= 2.17.0'
  gem 'rubocop-rspec'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'spring-watcher-listen', '>= 2.0.0'
  gem 'web-console', '>= 4.2.0'
end

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails', '>= 2.8.1'
  gem 'factory_bot_rails', '>= 6.2.0'
  gem 'faker'
  gem 'rb-readline'
  gem 'rspec-rails', '>= 6.0.1'
end

group :test do
  gem 'capybara', '>= 3.37.1'
  gem 'database_cleaner'
  gem 'launchy', '>= 2.5.0'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webdriver'
end
