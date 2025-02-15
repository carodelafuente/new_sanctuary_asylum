source 'https://rubygems.org'

ruby File.read('.ruby-version').strip

gem 'rails', '~> 5.2.2.x'

gem 'airbrake', '~> 6.2'
gem 'american_date'
gem 'brakeman'
gem 'carrierwave', '~> 1.0'
gem 'carrierwave-aws'
gem 'chosen-rails'
gem 'devise', '~> 4.7'
gem 'devise_invitable', '~> 1.7'
gem 'devise-security'
gem 'faker', require: false
gem 'filterrific', '~> 5.x'
gem 'geography_helper'
gem 'jbuilder', '~> 2.0'
gem 'jquery-rails'
gem 'jquery-ui-rails', '~> 6.0'
gem 'multi_json', '~> 1.11'
gem 'newrelic_rpm'
gem 'nokogiri', '~> 1.10'
gem 'non-stupid-digest-assets'
gem 'pg', '~> 1.1'
gem 'pg_search'
gem 'phantomjs'
gem 'puma'
gem 'redis', '~> 3.3'
gem 'sass-rails', '~> 5.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'simple_calendar', '~> 2.0'
gem 'textacular', '~> 5.0'
gem 'timecop' #used for seed data on staging
gem 'turbolinks', '~> 5.x'
gem 'will_paginate', '~> 3.1'

group :assets do
  gem 'coffee-rails'
  gem 'sprockets'
  gem 'uglifier'
end

group :development, :test do
  gem 'bundler-audit'
  gem 'byebug'
  gem 'capybara', '~> 2.10', require: false
  gem 'capybara-email'
  gem 'database_cleaner', '~> 1.5', require: false
  gem 'dotenv-rails'
  gem 'factory_bot_rails', '~> 4.0', require: false
  gem 'launchy', require: false
  gem 'poltergeist', '~> 1.11', require: false
  gem 'pry'
  gem 'rails-controller-testing'
  gem 'rspec-given', '~> 3.8', require: false
  gem 'rspec-rails', '~> 3.5', require: false
  gem 'rubocop'
  gem 'shoulda-matchers', '~> 3.1', require: false
  gem 'simplecov'
  gem 'webmock', '~> 2.1', require: false
end

group :production do
  gem 'rack-attack'
  gem 'sendgrid-ruby', '~> 5.2'
  gem 'skylight'
end

group :development do
  gem 'listen', '~> 3.0'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'spring-watcher-listen', '~> 2.0'
  gem 'tocer', '~> 9.1'
  gem 'web-console', '~> 3.0'
end

