source 'http://rubygems.org'

gem 'rails'
gem 'jquery-rails'
gem 'openid_connect', '0.2.0'
gem 'html5_validators'
gem 'squeel'
gem 'rest-client'

group :development, :test do
  gem 'sqlite3'
end

group :test do
  gem 'turn', :require => false
end

group :production do
  gem 'pg'
  gem 'rack-ssl', :require => 'rack/ssl'
end