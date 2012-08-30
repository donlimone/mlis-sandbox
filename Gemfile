source 'https://rubygems.org'

gem 'rails', '3.2.8'
gem 'rails-i18n'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.5'
  gem 'coffee-rails', '~> 3.2.2'

  # Using Twitter-Bootstrap fpr easy styling
  gem 'bootstrap-sass', '~> 2.0.3'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.2.3'

  gem 'haml_coffee_assets'

  gem 'i18n-js'
end

gem 'jquery-rails'

# HAML-Templating
gem 'haml-rails', '~> 0.3.4'

# MongoDB
#gem 'mongoid', '~> 3.0.3'

# Pretty URLs
#gem 'mongoid_slug', github: 'hakanensari/mongoid-slug', branch: '0.20.0'

# Paging
gem 'kaminari', '~> 0.13.0'

# Authentication
gem 'devise', '~> 2.1.1'
gem 'cancan', '~> 1.6.7'

# Forms
gem 'simple_form', '~> 2.0.2'
#gem "nested_form", :git => 'git://github.com/ryanb/nested_form.git'

# BackboneJS
gem 'backbone-on-rails'

# JSON/XML-API builder
gem 'rabl'

# Use unicorn as the app server
gem 'unicorn'

gem 'resque'
gem 'resque-scheduler', require: 'resque/scheduler'

group :production do
  gem 'pg', '0.12.2'
end

# DEVELOPMENT ONLY
group :development do
  # Deploy with Capistrano
  gem 'capistrano'

  gem 'capistrano-resque', '~> 0.0.6'

  # To use debugger
  # gem 'debugger'
end

# TEST ONLY
group :test do
  # ContinuousIntegration reports for jenkins (a.k.a hudson)
  gem 'ci_reporter', require: false
  gem "cucumber-rails", require: false
  # Code Coverage
  gem 'simplecov', require: false
  gem 'simplecov-html', require: false
  gem 'simplecov-rcov', require: false
end

# TESTS AND DEVELOMENT
group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.10.0'
  gem 'factory_girl_rails'
  gem 'rb-fsevent'
  gem 'growl'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'guard-bundler'
  gem 'spork', '~> 0.9.2'
  gem 'rspec'
  #gem 'mongoid-rspec'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'cucumber'
end

