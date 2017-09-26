source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.3.3'

gem 'rails', '~> 5.0.6'
gem 'sqlite3', group: [:development, :test]

gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.2'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'hirb', '~> 0.7.3'
gem 'devise', '~> 4.3'
gem 'stripe', '~> 3.3', '>= 3.3.1'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'paperclip', '~> 5.1'

gem 'jquery-rails'
# gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

group :production do
    gem 'pg'
    gem 'rails_12factor'
end

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
