source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'

gem 'rails', '~> 7.0.3'

# Core
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'redis', '~> 4.0'
gem 'slim-rails'

# Assets
gem 'cssbundling-rails'
gem 'jsbundling-rails'
gem 'sassc-rails'
gem 'sprockets-rails'

# UI
# gem 'rapid_ui', path: '~/src/hobbies/rapid_ui'

gem 'rapid_ui'
gem 'view_component'

# JS Frameworks
gem 'stimulus-rails'
gem 'turbo-rails'

gem 'bootsnap', require: false
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'rubocop-rails', require: false
end

group :development do
  gem 'web-console'
end
