source 'http://rubygems.org'

gem 'rails', '~> 3.1.0'

gem 'haml', '~> 3.2.0.alpha'
gem 'oa-oauth'
gem 'twitter', '~> 2.0.0.rc.2'

platforms :jruby do
  gem 'jruby-openssl'
end

group :production do
  gem 'pg'
  gem 'thin'
end

group :test do
  gem 'mocha'
  gem 'simplecov'
  gem 'webmock'
end
