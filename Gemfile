source 'https://rubygems.org'
fury_url = ENV['GEMFURY_URL']
source fury_url if fury_url

gem 'rails', '4.1.8'
gem 'pg'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'thin'
gem 'haml'
gem 'compass-rails'
gem 'redcarpet'
gem 'formtastic'
gem 'carrierwave'
gem 'fog'
gem 'mini_magick'
gem 'jsl-identity', '= 0.0.7', require: 'jsl/identity' # for accessing user identities (comes from Gemfury)
gem 'deject'                                           # dependency injection

group :development, :test do
  gem 'minitest'
  gem 'minitest-emoji'
  gem 'capybara'
  gem 'pry'
  gem 'launchy'
end

group :production do
  gem 'rails_12factor'
end