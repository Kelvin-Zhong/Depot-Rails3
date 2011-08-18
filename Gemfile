source 'http://rubygems.org'

gem 'rails', '3.1.0.rc6'
gem 'json'
gem 'sass'
gem 'coffee-script'
gem 'uglifier'
# Rails 3.1 - JavaScript
gem 'jquery-rails'


# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'rake', '~> 0.8.7'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

gem 'will_paginate', '>= 3.0.pre'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:

# Rails Admin https://github.com/sferik/rails_admin
gem 'fastercsv' # Only required on Ruby 1.8 and below, left in for fun
gem 'devise' # Devise must be required before RailsAdmin
gem 'rails_admin', :git => 'git://github.com/sferik/rails_admin.git'

group :development, :test do
  gem 'sqlite3'
  gem 'RedCloth'
end

group :production do
  gem 'mysql'
end
