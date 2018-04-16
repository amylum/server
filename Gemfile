path = File.dirname(ENV['BUNDLE_GEMFILE'] || '.')
ruby File.read(File.join(path, '.circle-ruby')).chomp
source 'https://rubygems.org'

gem 'herokuconf', '~> 0.0.8'
gem 'puma', '~> 3.10.0'
gem 'rack-ssl', '~> 1.4.1'
gem 's3repo', '~> 1.0.0'
gem 'sinatra', '~> 2.0.0'

group :development do
  gem 'codecov', '~> 0.1.1'
  gem 'fuubar', '~> 2.3.0'
  gem 'goodcop', '~> 0.5.0'
  gem 'rake', '~> 12.3.0'
  gem 'rspec', '~> 3.7.0'
  gem 'rubocop', '~> 0.55.0'
end
