source 'https://rubygems.org'

ruby '2.5.0'

gem 'rails', '~> 5.1.6'

gem 'mysql2', '0.5.1'
gem 'sequel', '5.9.0'
gem 'sequel-rails', '1.0.1'

gem 'foreman'
gem 'puma'
gem 'sidekiq', '5.1.3'
gem 'whenever', '0.10.0', :require => false

group :development do
  gem "capistrano", "~> 3.8"
  gem 'capistrano-bundler', '~> 1.1.2'
  gem 'capistrano-rails', '~> 1.1.1'
  gem 'capistrano-sidekiq' , git: 'git@github.com:seuros/capistrano-sidekiq.git'
end

group :development, :test do
  gem 'apitome'
  gem 'factory_bot_rails', '~> 4.0'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'rspec-rails', '~> 3.5'
  gem 'rspec_api_documentation', '~> 5.1.0'
  gem 'rspec_junit_formatter', '0.2.2'
  gem 'simplecov', require: false
  gem 'spring'
end

group :test do
  gem 'database_cleaner'
end
