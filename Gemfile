source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5'

# Use PostgreSQL as the database for Active Record
gem 'pg'
gem 'pg_search'
gem 'will_paginate'

gem 'puma'

# Caching
gem 'dalli'

# Disabling assets; replaced with Gulp
# gem 'sass-rails', '~> 5.0'
# gem 'uglifier', '>= 1.3.0'
# gem 'coffee-rails', '~> 4.1.0'
# gem 'jquery-rails'

# Back-end App is treated mostly as a JSON API
gem 'jbuilder', '~> 2.0' # Build JSON APIs with ease
gem 'rails-api' # pare down rails to act like an API; disabling unnecessary middleware
gem 'rack-cors', :require => 'rack/cors'

# Rails app configuration / ENV management
gem 'figaro'

# User management / auth
gem 'devise_token_auth'
gem 'omniauth-google-oauth2'
gem 'omniauth-facebook'

# Parsers for project asset precompilation
gem 'redcarpet'
gem 'ejs'
gem 'execjs'

# For audio transcripts
gem 'popuparchive'
gem 'webvtt-ruby'

# Error logging
gem 'newrelic_rpm'
gem 'rails_12factor'

# Use unicorn on linux only
platforms :ruby do # linux
  gem 'unicorn'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.4'
end

group :development do
  gem 'capistrano'
  gem 'capistrano3-puma'
  gem 'capistrano-rails', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rvm'
end
