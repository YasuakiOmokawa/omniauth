source 'https://rubygems.org'

gem 'jruby-openssl', '~> 0.10.5', platforms: :jruby
gem 'rake', '>= 12.0'
gem 'yard', '>= 0.9.11'

gem 'debug' # デバッガ

group :development do
  gem 'benchmark-ips'
  gem 'kramdown'
  gem 'memory_profiler'
  gem 'pry'
end

group :test do
  gem 'coveralls_reborn', '~> 0.19.0', require: false
  gem 'hashie', '>= 3.4.6', '~> 4.0.0', platforms: [:jruby_18]
  gem 'json', '~> 2.3.0', platforms: %i[jruby_18 jruby_19 ruby_19]
  gem 'mime-types', '~> 3.1', platforms: [:jruby_18]
  gem 'rack-test'
  gem 'rest-client', '~> 2.0.0', platforms: [:jruby_18]
  gem 'rspec', '~> 3.5'
  gem 'rack-freeze'
  gem 'rubocop', '>= 0.58.2', '< 0.69.0', platforms: %i[ruby_20 ruby_21 ruby_22 ruby_23 ruby_24]
  gem 'simplecov-lcov'
  gem 'tins', '~> 1.13', platforms: %i[jruby_18 jruby_19 ruby_19]
end

gemspec
