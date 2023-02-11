# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'rails', '~> 6.1.3', '>= 6.1.3.2'

gem 'activerecord-import', '~> 1.4.1'
gem 'bcrypt'
gem 'bootsnap', '>= 1.4.4', require: false

gem 'caxlsx', '~> 3.1'
gem 'caxlsx_rails', '~> 0.6'
gem 'rubyXL', '~> 3.4'

gem 'draper', '~> 4.0'
gem 'pagy', '~> 6.0.1'
gem 'puma', '~> 6.0.2'
gem 'rails-i18n'
gem 'rubyzip', '~> 2'
gem 'sqlite3', '~> 1.4'
gem 'valid_email2', '~> 4.0.5'
gem 'webpacker', '~> 6.0.0.rc.6'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'faker', '~> 3.1.1'
  gem "debug", require: false
  gem 'pry-rails'
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 3.0'
  gem 'rubocop', '~> 1.45.1', require: false
  gem 'rubocop-performance', '~> 1.16', require: false
  gem 'rubocop-rails', '~> 2.11', require: false
  gem 'spring'
  gem 'web-console', '>= 4.1.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
