source 'https://rubygems.org'
ruby '2.4.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.2'
gem 'webpacker', '~> 3.0'

# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# A fast, safe and extensible Markdown to (X)HTML parser
gem 'redcarpet', '~> 3.4.0'

# Rouge aims to a be a simple, easy-to-extend drop-in replacement for pygments.
gem 'rouge', '~> 2.0.7'

# Toolkit for processing input using filters and pipelines
gem 'banzai', '~> 0.1.2'

# ZURB Foundation on Sass/Compass
gem 'foundation-rails', '6.4.1.2'

# Nokogiri (鋸) is an HTML, XML, SAX, and Reader parser. Among Nokogiri's many features is the ability to search documents via XPath or CSS3 selectors.
gem 'nokogiri', '1.7.0.1'

# Autoload dotenv in Rails.
gem 'dotenv-rails', groups: [:development, :test]

# Ruby/ProgressBar is a text progress bar library for Ruby.
gem 'ruby-progressbar'

gem 'rubocop'

# Ruby notifier for bugsnag.com
gem 'bugsnag'

# Extends String class or add a ColorizedString with methods to set text color, background color and text effects.
gem 'colorize'

# A simple Ruby client for the algolia.com REST API
gem 'algoliasearch'

# A simple HTTP and REST client for Ruby, inspired by the Sinatra microframework style of specifying actions: get, put, post, delete.
gem 'rest-client'

# Helpers for the reCAPTCHA API
gem 'recaptcha', require: "recaptcha/rails"

# Implements the iCalendar specification (RFC-5545) in Ruby.
gem 'icalendar'

# A parser for Open API specifications
gem 'open_api_parser', github: 'nexmo/open_api_parser', branch: 'openapi-specification-v3'

# Generate JSON strings from Ruby objects with flexible formatting options.
gem 'neatjson'

# Faker, a port of Data::Faker from Perl, is used to easily generate fake data: names, addresses, phone numbers, etc.
gem 'faker', '1.8.4'

# factory_girl_rails provides integration between factory_girl and rails 3 or newer (currently just automatic factory definition loading)
gem 'factory_girl_rails', '4.8.0'

# A slim ruby wrapper for posting to slack webhooks
gem 'slack-notifier', '2.3.1'

# The administration framework for Ruby on Rails.
gem 'activeadmin', '1.1.0'

# Flexible authentication solution for Rails with Warden
gem 'devise', '4.3.0'

gem 'nexmo_api_specification', '0.1.3'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'rawler', git: 'https://github.com/oscardelben/rawler.git', require: false
  gem 'rspec-rails', '~> 3.5'
  gem 'pry'
  gem 'awesome_print'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'listen', '~> 3.0.5'
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'guard-livereload', '~> 2.5', require: false
  gem 'guard-rspec'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry'

  # Share git hooks in Ruby projects among all the collaborators automatically, without them having to do anything
  gem 'git-hookshot', git: 'https://github.com/brandonweiss/git-hookshot.git'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
