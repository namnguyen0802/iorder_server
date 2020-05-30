source "https://rubygems.org"

#basic
gem "rails", "5.1.2"
gem "puma", "~> 3.0"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "jquery-rails"
gem "jbuilder", "~> 2.5"

#database
gem "mysql2", ">= 0.3.18", "< 0.5"

#config
gem "config"

#encrypt
gem "bcrypt"

#upload file
gem "carrierwave"
gem "fog"

#front-end
gem "kaminari"

#api
gem "doorkeeper"
gem "active_model_serializers"

#background job
gem "sidekiq"
gem "redis"

#search
gem "ransack"

gem 'ed25519', '~> 1.2'
gem 'bcrypt_pbkdf', '~> 1'

group :development, :test do
  gem "dotenv-rails"
  gem "faker"
  gem "pry-rails"
  gem "capistrano"
  gem "capistrano3-puma"
  gem "capistrano-rails", require: false
  gem "capistrano-bundler", require: false
  gem "capistrano-rvm"
  gem 'capistrano-ssh-doctor', '~> 1.0'
end

group :development do
  gem "listen", "~> 3.0.5"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
