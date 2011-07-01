source 'http://rubygems.org'

gem 'rails', '3.0.7'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'


#DB
gem 'sqlite3' # using this on Heroku for now
gem 'mysql2' # this is what i'm using locally, so i can see what's going on
gem 'taps' # this is necessary to allow the "heroku db:push" command to send my SQL contents to heroku's so-called 'shared db'

#BDD (these were recommended in the 'Setting up a Rails Project' section of The RSpec Book)
group :development, :test do
    gem "rspec-rails", ">= 2.0.0"
    gem "cucumber-rails", ">= 0.3.2" 
    gem "webrat", ">= 0.7.2"
    gem "database_cleaner", ">= 0.5.2"
    gem "selenium-client", ">= 1.2.18"
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
