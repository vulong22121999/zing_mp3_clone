source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'active_storage_validations', '~> 0.1'
gem 'amoeba', '~> 3.0'
gem 'awesome_rails_console', '~> 0.4.4'
gem 'aws-sdk-s3', require: false
gem 'blueprinter'
gem 'bootstrap-tooltip-rails', '~> 0.1'
gem 'coffee-rails', '~> 5.0.0'
gem 'devise', '~> 4.7', '>= 4.7.1'
gem 'doorkeeper'
gem 'discard', '~> 1.2'
gem 'ffaker'
gem 'geocoder', '~> 1.6', '>= 1.6.3'
gem 'geokit-rails', '~> 2.3', '>= 2.3.1'
gem 'httparty'
gem 'image_processing'
gem 'jbuilder', '~> 2.5'
# gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'material_icons'
gem 'pagy', '~> 3.5'
gem 'paperclip', '~> 6.0.0'
gem 'pg'
gem 'phonelib', '~> 0.6.44'
gem 'puma', '~> 3.7'
gem 'rails', '~> 6.0.1'
gem 'rails_sortable'
gem 'sass-rails', '~> 5.0'
gem 'sidekiq'
gem 'simple_form'
gem 'turbolinks', '~> 5'
gem 'twilio-ruby', '~> 5.39.2'
gem 'uglifier', '>= 1.3.0'
gem 'geocoder', '~> 1.6', '>= 1.6.3'
gem "action_policy"
gem 'pg_search'

group :development, :test do
  gem 'annotate'
  # gem 'better_errors'
  gem 'bullet'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'guard'
  gem 'guard-livereload'
  gem 'hirb'
  gem 'hirb-unicode-steakknife', require: 'hirb-unicode'
  gem 'pry', '~> 0.12.2'
  gem 'pry-byebug', '~> 3.7'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'rb-readline'
  gem 'selenium-webdriver'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rails-erd'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Please clean up duplicated gems if any.
# Feel free to remove gems that you don't want to use or if they conflict with other gem dependencies. (you might need to update .pryrc also)
