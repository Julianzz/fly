source 'https://rubygems.org'

gem 'active_model_serializers', git: 'https://github.com/rails-api/active_model_serializers.git'

# we had issues with latest, stick to the rev till we figure this out
# PR that makes it all hang together welcome
gem 'ember-rails', git: 'https://github.com/emberjs/ember-rails.git', ref: '57bbe32'
gem 'barber', '0.3.0'
gem 'ember-source', '1.0.0.rc6.4' # or the version you need

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

#add for auth
gem 'devise'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end


group :development, :test do
  gem 'rspec-rails', '~> 2.0'
  gem 'jshint_on_rails'
  gem 'listen', require: false
  gem 'guard-jshint-on-rails', require: false
  gem 'certified', require: false
  gem 'fabrication', require: false
  gem 'guard-jasmine', require: false
  gem 'guard-rspec', require: false
  gem 'guard-spork', require: false
  gem 'mocha', require: false
  gem 'rb-fsevent', require: RUBY_PLATFORM =~ /darwin/i ? 'rb-fsevent' : false
  gem 'rb-inotify', '~> 0.9', require: RUBY_PLATFORM =~ /linux/i ? 'rb-inotify' : false
  gem 'shoulda', require: false
  gem 'simplecov', require: false
  gem 'terminal-notifier-guard', require: false
  gem 'timecop'
  gem 'rspec-given'
end


group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'librarian', '>= 0.0.25', require: false
  gem 'pry-rails'
  # https://github.com/ctran/annotate_models/pull/106
  gem 'annotate', :git => 'https://github.com/SamSaffron/annotate_models.git'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
