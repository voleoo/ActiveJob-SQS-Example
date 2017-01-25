source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', github: 'rails/rails', branch: '4-2-stable'
gem 'sqlite3'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'aws-sdk-core'

group :development, :test do
  gem 'pry-byebug'
  gem 'spring'
end

group :development do
  gem 'mailcatcher'
end
