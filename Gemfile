source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# use HAML for the views
gem 'haml'

#use SimpleForm to create forms faster
gem 'simple_form'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

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

group :development do
  # Use sqlite3 as the database for Active Record in development
  gem 'sqlite3', '1.3.8'
end

group :development, :test do
  # Use haml-rails to generate haml while scaffolding
  gem 'haml-rails'
end

group :production do
  #user pg as database for Active Record in production
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

group :test do
  #Database_cleaner to clean your DB while testing
  gem 'database_cleaner'
  #Rspec Cucumber and Capybara  in rails
  gem 'rspec-rails'
  gem 'cucumber-rails',:require => false
  gem 'capybara'
end

# Use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.1.2'
