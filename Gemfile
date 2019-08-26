# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.0'

gem 'bootsnap', require: false
gem 'coffee-rails'
gem 'jbuilder'
gem 'jwt'
gem 'octokit'
gem 'puma'
gem 'sass-rails'
gem 'sqlite3'
gem 'turbolinks'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
gem 'uglifier'

group :development do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'web-console'
end

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails'
end

group :test do
  gem 'capybara'
  gem 'chromedriver-helper'
  gem 'selenium-webdriver'
end
