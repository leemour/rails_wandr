source 'https://rubygems.org'

gem 'rails', '3.2.12'
# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem "haml", ">= 3.1.6"
gem "bootstrap-sass", ">= 2.0.4.0"
gem 'jquery-rails'

group :development, :test do
  gem 'sqlite3'
  gem "haml-rails", ">= 0.3.4"
  gem 'debugger'
  gem 'database_cleaner'
  gem 'launchy'
  #gem 'newrelic_rpm'
  gem 'railroady'
end

group :production do
  gem 'pg'
end

group :test do
  gem 'rspec-rails'
  gem 'spork-rails'
  gem 'simplecov'
  gem 'capybara'
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'factory_girl'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'compass'
  gem "therubyracer", :platform => :ruby
  gem 'uglifier', '>= 1.0.3'
  gem 'redcarpet'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'