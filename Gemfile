source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'rails', '~> 6.1.0'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'devise', '~> 4.7', '>= 4.7.3'
gem 'bundler', '~> 2.1', '>= 2.1.4'

group :development, :test do
  gem 'byebug', '~> 11.1', '>= 11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'sqlite3', '~> 1.4'
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
end

group :production do
  gem 'pg', '~> 1.2', '>= 1.2.3'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '~> 3.142', '>= 3.142.7'
  gem 'webdrivers', '~> 4.4', '>= 4.4.2'
end

gem 'tzinfo-data', '~> 1.2020', '>= 1.2020.6', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
