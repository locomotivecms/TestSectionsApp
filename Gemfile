source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.0'

gem 'bundler', '1.17.3'

gem 'mongoid'
gem 'devise'

# gem 'pry'
# gem 'custom_fields', path: '../custom_fields' # for Developers
# gem 'locomotivecms_common', path: '../common', require: false
# gem 'locomotivecms_steam', path: '../steam', require: false
# gem 'locomotivecms', path: '../engine'
# gem 'locomotivecms_search', path: '../search'

gem 'locomotivecms', github: 'locomotivecms/engine', ref: '48bb396b'
gem 'locomotivecms_steam', github: 'locomotivecms/steam', ref: '034eece', require: false
gem 'locomotivecms_common', github: 'locomotivecms/common', ref: 'c2a1c48', require: false
gem 'locomotivecms_search', github: 'locomotivecms/search', ref: '35e5813'
gem 'custom_fields', github: 'locomotivecms/custom_fields', ref: '251b1b9', require: false

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.3'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# gem 'passenger-rails'
gem 'rack-cors', require: 'rack/cors'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'carrierwave-aws'

# gem 'sidekiq'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

group :production do
  gem 'newrelic_rpm'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
