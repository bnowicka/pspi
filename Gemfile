source 'https://rubygems.org'

gem 'rails', '3.2.14'

gem 'sqlite3', :group => :development

group :development do
  gem "less-rails", '= 2.3.3'
  # silence assets pipeline log messages
  gem 'quiet_assets'
  # quickly see your routes under /rails/routes
  gem 'sextant'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
  gem "less-rails-bootstrap", :group => :assets
end

gem 'jquery-rails'

# Use thin as the app server
gem 'thin'

gem 'rubygems-bundler'
