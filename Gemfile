if ENV['RUBYTAOBAO']
  source 'http://ruby.taobao.org'
else
  source 'https://rubygems.org'
end

ruby '2.0.0'

gem 'rails', '4.0.4'
gem 'sass-rails', '~> 4.0.2'
gem 'coffee-rails', '~> 4.0.1'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'foundation-rails', '~> 5.2.1'
gem 'foundation-icons-sass-rails'

gem 'mongoid'
gem 'mongoid-pagination'
gem 'redcarpet'
gem 'rouge'
gem 'slim-rails'
gem 'simple_form'
gem 'mini_magick'
gem 'carrierwave-mongoid'
gem 'html_truncator'
gem 'nokogiri'
gem 'angularjs-rails'
gem 'figaro'
gem 'rqrcode-with-patches', require: 'rqrcode'
gem 'chunky_png'
gem 'sidekiq'
gem 'rest-client'

group :development do
  gem 'quiet_assets'
  gem 'guard'
  gem 'guard-rails'
  gem 'guard-rspec', require: false
  gem 'guard-bundler', require: false
end

group :test do
  gem 'capybara'
  gem 'mongoid-rspec', :require => false
  gem 'database_cleaner'
  gem 'rspec-sidekiq'
end

group :test, :development do
  gem "rspec-rails", ">= 2.8.1"
  gem 'pry-rails'
  gem 'pry-nav'
  gem 'factory_girl_rails'
end
