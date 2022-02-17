# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.0'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.2'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'sprockets-rails', '~> 3.4', '>= 3.4.2'

# Use pg as the database for Active Record
gem 'pg', '~> 1.3', '>= 1.3.1'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.6'

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem 'importmap-rails', '~> 1.0', '>= 1.0.2'

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem 'turbo-rails', '~> 1.0', '>= 1.0.1'

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'stimulus-rails', '~> 1.0', '>= 1.0.2'

# Use Tailwind CSS [https://github.com/rails/tailwindcss-rails]
gem 'tailwindcss-rails', '~> 2.0', '>= 2.0.5'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder', '~> 2.11', '>= 2.11.5'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.6'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '~> 1.10', '>= 1.10.3', require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# For external HTTP requests
gem 'httparty', '~> 0.20.0'

group :development, :test do
  # Detects N+1 queries and unused eager loading
  gem 'bullet', '~> 7.0.1'
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', '~> 1.4', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails', '~> 2.7.6'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'faker', '~> 2.19'
  gem 'rspec-rails', '~> 5.1.0'
  gem 'rubocop-rails', '~> 2.13.2', require: false
end

group :development do
  # Annotates models, routes, fixtures, and other files based on the database schema.
  gem 'annotate', '~> 3.2'
  # Detects security vulnerabilities in Ruby on Rails applications via static analysis
  gem 'brakeman', '~> 5.2.1'
  # Preview email in the default browser instead of sending it
  gem 'letter_opener', '~> 1.7'
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'web-console', '~> 4.2'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara', '~> 3.36'
  gem 'selenium-webdriver', '~> 4.1'
  gem 'shoulda-matchers', '~> 5.1'
  # Code coverage for Ruby
  gem 'simplecov', '~> 0.21.2', require: false
  gem 'webdrivers', '~> 5.0'
end
