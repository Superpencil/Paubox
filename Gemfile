source 'https://rubygems.org'

# Bundler
gem 'bundler', '>= 1.8.4'
if ENV['HEROKU_APP_NAME']
  ruby '2.2.2'
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'
# Use postgres as the database for Active Record
gem 'pg', '~> 0.18.4'
# Use Puma as the app server
gem 'puma', '~> 3.6.0'
# Use HAML for HTML content
gem 'haml-rails', '~> 0.9.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use Locomotive as CMS
gem 'locomotivecms', '~> 3.1.1'

source 'https://rails-assets.org' do
  # Beautiful Select dropdowns
  gem 'rails-assets-chosen', '~> 1.6.2'
  # CSS Animations
  gem 'rails-assets-animate.css', '~> 3.5.2'
end
# Uploads to AWS
gem 'carrierwave-aws'
# API
gem 'platform-api', '~> 0.3.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Heroku gem
group :production do
  gem 'rails_12factor'
end

# Ruby version
ruby '2.3.1'
