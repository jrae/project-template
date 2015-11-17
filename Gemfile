source 'https://rubygems.org'
ruby "2.2.2"
gem 'rails', '4.2.3'

# UI
gem 'neat'
gem 'bourbon'
gem 'bitters'
gem 'haml-rails'
gem 'jquery-rails'
gem 'sass-rails'
gem 'normalize-rails'
gem 'draper'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# DB
gem 'pg'

group :development do
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem 'rspec-given',  :require => false
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'poltergeist'
  gem "webmock"
  gem "vcr"
end

group :development, :test do
  gem 'byebug'
end

# IF HEROKU
# group :production, :staging do
#   gem 'rails_12factor'
# end