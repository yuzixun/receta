source 'https://ruby.taobao.org'


gem 'rails', '>= 5.0.0.beta3', '< 5.1'
gem 'sqlite3'
gem 'unicorn', '~> 5.0.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'

group :doc do
  gem 'sdoc', require: false
end

group :development, :test do
  gem 'byebug'
  gem 'rspec-rails', '~> 2.0'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'selenium-webdriver'
  gem 'teaspoon-jasmine'
  gem 'phantomjs'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "foreman"
group :production, :staging do
  gem "rails_12factor"
  gem "rails_stdout_logging"
  gem "rails_serve_static_assets"
end

# for manager front-end assets
gem 'bower-rails'
gem 'angular-rails-templates'

