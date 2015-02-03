source 'https://rubygems.org'

gem 'rails', '4.2'

gem 'angularjs-rails'
gem 'anjlab-bootstrap-rails', require: 'bootstrap-rails',
                              github: 'anjlab/bootstrap-rails',
                              branch: '3.0.0'

gem 'bootstrap-kaminari-views'

gem 'google-analytics-rails'

gem 'jbuilder', '~> 1.2'
gem 'jquery-rails'
gem 'jquery-ui-rails'

gem 'kaminari'

gem 'marked-rails'

gem 'rails-env'
gem 'redcarpet'

gem 'sass-rails', '~> 4.0.0'
gem 'simple_form', '~> 3.1.0.rc1', github: 'plataformatec/simple_form'

gem 'therubyracer', platforms: :ruby
gem 'turbolinks'

gem 'uglifier', '>= 1.3.0'

gem 'vuejs-rails'

group :production do
  gem 'pg'
  gem 'rails_12factor', '0.0.2'
end

group :development do
  gem 'clean_logger'
  gem 'overcommit', require: false
  gem 'rubocop', require: false
  gem 'sqlite3'
end

group :test, :development do
  gem 'fabrication'
  gem 'faker'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 3.1.0'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner', '1.2.0'
  gem 'factory_girl', '~> 4.0'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

ruby '2.2.0'
