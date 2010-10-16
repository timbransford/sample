source 'http://rubygems.org'

gem 'rails', '3.0.0'

group :development do
  gem 'rspec-rails', '>=2.0.0'
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

group :test do
  gem 'rspec', '>=2.0.0'
  gem 'webrat'
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

group :production, :staging do
  gem 'pg'
end