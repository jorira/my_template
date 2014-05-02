source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0'

# Use postgresql as the database for Active Record
gem 'pg'

# Use SCSS for stylesheets
#gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
#gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
#gem 'debugger', group: [:development, :test]
#

group :development, :test do
  gem 'thin'
  gem 'debugger'
end

group :test do
  gem 'rspec-rails'           #Rspec.
  gem 'factory_girl_rails'     #facorygirl for test.
  gem 'spork'         # DRB server
  gem 'guard'                # AutoTest
  gem 'guard-spork'            # for sport on guard
  gem 'guard-rspec'             # for rspec on guard
  # gem 'guard-cucumber', '1.3.2'          # for cucumber on guard
  # gem 'cucumber-rails', '1.3.0', :require => false    #cucumber on rails
  gem 'simplecov', :require => false  #coverage lib
  # gem 'database_cleaner', '0.9.1' # database_cleaner is not required, but highly recommended
  #gem 'turn', :require => false # Pretty printed test output
end

gem 'devise'
