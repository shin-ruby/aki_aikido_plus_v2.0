source 'http://rubygems.org'

gem 'rails', '~> 4.2.7.1'

gem 'sass-rails', '~> 5.0'
gem 'uglifier', require: false
gem 'coffee-rails', '~> 4.2.1'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootswatch-rails', '~> 3.3.5'
gem 'font-awesome-rails', '~> 4.6'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks', '~> 2.5.3'
gem 'jbuilder', '~> 2.0'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'pg'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
#gem 'unicorn'

# Use Capistrano for deployment
group :development do
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-rvm'
  gem 'capistrano-passenger'
end

group :development, :test do
  gem 'byebug'
  gem 'web-console'
  gem 'spring', platform: :ruby
end

group :test do
  gem 'pry', platform: :ruby
  gem 'minitest'
  gem 'mini_backtrace', '~> 0.1.3'
  gem 'factory_girl_rails', '~> 4.5'
end

gem 'refinerycms', '~> 3.0.4'
gem 'quiet_assets', group: :development
gem 'refinerycms-acts-as-indexed', ['~> 2.0', '>= 2.0.0']
gem 'refinerycms-wymeditor', ['~> 1.0', '>= 1.0.6']
gem 'refinerycms-authentication-devise', '~> 1.0'

gem 'refinerycms-news', github: 'refinery/refinerycms-news', branch: 'master'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
