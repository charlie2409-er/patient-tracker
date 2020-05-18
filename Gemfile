source 'https://rubygems.org'
ruby '2.1.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.1'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
gem 'devise', '~> 4.7.1'
# Simple, Heroku-friendly Rails app configuration using ENV and a single YAML file
gem 'figaro', '>= 1.0.0.rc1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 3.1.0'
gem 'newrelic_rpm', '~> 3.9.0.229'
# Use pundit for minimal authorization through OO design and pure Ruby classes
gem 'pundit', '~> 0.2.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '~> 2.2.2'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use unicorn as the app server
# gem 'unicorn'


group :development do
  # Use Capistrano for deployment
  # gem 'capistrano-rails'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 1.1.3'
end

group :development, :test do
  gem 'better_errors', '~> 1.1.0'
  # Use debugger
  # gem 'debugger', group: [:development, :test]
  gem 'binding_of_caller', '~> 0.7.2'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '~> 1.3.9'
end

group :production do
  gem 'pg', '~> 0.17.1'
  gem 'rails_12factor', '~> 0.0.2'
end

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc
