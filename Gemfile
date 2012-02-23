source 'https://rubygems.org'

gem 'rails', '3.2.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mongoid'
gem 'bson_ext'

# Authentication and authorization
gem 'devise'
gem 'cancan'

gem 'omniauth'
gem 'omniauth-facebook'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
  gem 'eco'
end

gem 'jquery-rails'
gem 'backbone-rails'
gem 'compass-rails', '~> 1.0.0.rc.3'
gem 'zocial'

gem 'thin'

# Background workers
gem 'hiredis'
gem 'redis', require: ['redis/connection/hiredis', 'redis']
gem 'resque', require: 'resque/server'

group :development, :test do
  gem 'rspec-rails'
  gem 'mongoid-rspec'

  gem 'capybara'

  gem 'database_cleaner'
  gem 'faker'
  gem 'factory_girl_rails'

  gem 'jasminerice'

  gem 'spork-rails'
  gem 'simplecov'

  gem 'guard'
  gem 'ruby_gntp'

  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-jasmine'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
