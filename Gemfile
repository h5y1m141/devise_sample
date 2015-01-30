source 'https://rubygems.org'


gem 'rails', '4.2.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'devise'
gem 'mysql2'

group :development do
  gem 'thin'
  gem 'annotate'
  gem 'web-console', '~> 2.0'
  gem 'guard-bundler', require: false
  gem 'guard-rails', require: false
  gem 'guard-rspec', require: false
  gem 'guard-resque', require: false
  gem 'rubocop', require: false
end

group :development, :test do
  gem 'byebug'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'factory_girl_rails'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
end

group :test do
  gem 'rspec'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'headless'
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'fakeredis', require: 'fakeredis/rspec'
end

group :deployment do
  # gem 'ops', bitbucket: 'heathrow/ops'
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'cap-ec2'
end
