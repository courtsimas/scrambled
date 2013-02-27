source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '3.2.12'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'airbrake'
gem 'thin'
gem 'pg'
gem 'haml'

group :development do
  gem 'foreman'
end

group :development, :test do
  gem 'guard'
  gem 'guard-spork'
  gem 'sham_rack'
end

group :test do
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'simplecov', require: false
  gem 'timecop'
end

group :staging, :production do
  gem 'newrelic_rpm'
end