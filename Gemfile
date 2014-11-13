source 'https://rubygems.org'

gemspec

gem 'dotenv'

gem 'rake'
gem 'rack-cache', :require => 'rack/cache'

gem 'thin'

group :development, :test do
  gem 'rack-test'
  gem 'rspec'
  gem 'webmock'
  gem 'fastimage'
end

group :production, :staging do
  gem 'newrelic_rpm', :require => false
end
