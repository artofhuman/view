source 'https://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '2.0.0.alpha1', require: false, git: 'https://github.com/hanami/utils.git', branch: 'unstable'
gem 'haml',         '~> 5.0', require: false
gem 'slim',         '~> 3.0', require: false

gem 'simplecov', require: false
gem 'coveralls', require: false
