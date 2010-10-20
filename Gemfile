source 'http://rubygems.org'

gem 'rails', '3.0.0'
gem 'gravatar_image_tag'
gem "will_paginate", "~> 3.0.pre2"

group :development do
  gem 'rspec-rails', '2.0.0'
  gem 'sqlite3-ruby', :require => 'sqlite3'
  gem 'annotate-models'
  gem 'faker', '0.3.1'
end

group :test do
  gem 'rspec', '2.0.0'
  gem 'webrat'
  gem 'sqlite3-ruby', :require => 'sqlite3'
  gem 'factory_girl_rails', '1.0'
end

group :production, :staging do
  gem 'pg'
end