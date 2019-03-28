source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.6', '>= 5.1.6.2'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]


#Application Gems

group :development do
  gem 'sqlite3', '~> 1.3.6'
end

gem 'haml', '~> 5.0', '>= 5.0.4'
gem 'devise', '~> 4.6', '>= 4.6.2'
gem 'paperclip', '~> 6.1'
gem 'simple_form', '~> 4.1'
gem 'acts_as_votable', '~> 0.12.0'


group :production do
  gem 'pg'
  gem 'rails_12factor'
end