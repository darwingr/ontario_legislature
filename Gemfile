source 'https://rubygems.org'

ruby '2.4.1'

gem 'airbrake'
gem 'autoprefixer-rails'
gem 'bourbon', '~> 4.2.0'
gem 'coffee-rails', '~> 4.2.0'
gem 'delayed_job_active_record'
gem 'email_validator'
gem 'flutie'
gem 'high_voltage'
gem 'i18n-tasks'
gem 'jquery-rails'
gem 'neat', '~> 1.8.0'
gem 'newrelic_rpm', '>= 3.9.8'
gem 'normalize-rails', '~> 4.1'
gem 'pg'
gem 'puma'
gem 'rack-canonical-host'
gem 'rails', '~> 5.1.2'
gem 'recipient_interceptor'
gem 'refills'
gem 'sass-rails', '~> 5.0'
gem 'simple_form'
gem 'title'
gem 'uglifier'

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'web-console'
end

group :development, :test do
  gem 'awesome_print'
  gem 'bundler-audit', require: false
  gem 'byebug'
  gem 'dotenv-rails'
  gem 'factory_girl_rails'
  gem 'guard'
  gem 'guard-rspec'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 3.5.0'
  gem 'terminal-notifier', require: false
  gem 'terminal-notifier-guard', require: false
end

group :test do
  gem 'capybara-webkit', '>= 1.2.0'
  gem 'database_cleaner'
  gem 'formulaic'
  gem 'launchy'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'simplecov', require: false
  gem 'timecop'
  gem 'webmock'
end

group :staging, :production do
  gem 'rails_stdout_logging'
  gem 'rack-timeout'
end
