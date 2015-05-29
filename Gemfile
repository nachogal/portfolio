source "https://rubygems.org"
ruby "2.2.0"
gem "rails", "~> 4.2.0"

# Email validations
gem "validates_email_format_of"

# user registration, authorization and authentication
gem "devise"
# to install the views, run: rails g devise:views:bootstrap_templates
gem "devise-bootstrap-views"

# form styling
gem "simple_form"

# fonts
gem "font-awesome-sass"

# CMS
# gem "casein"

# Delayed jobs
# gem "delayed_job_active_record"

# Activity Feed
# gem "public_activity"

# Avatars for users
# gem "gravtastic"

# Pagination
# gem "will_paginate", "~> 3.0"

# Add comments
# gem "acts_as_commentable"

# JQuery for turbolinks
gem "jquery-turbolinks" 
# Use SCSS for stylesheets
gem "sass-rails", "~> 5.0"
# Use Uglifier as compressor for JavaScript assets
gem "uglifier"
# Use CoffeeScript for .js.coffee assets and views
gem "coffee-rails", "~> 4.1.0"
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem "therubyracer",  platforms: :ruby

# Use jquery as the JavaScript library
gem "jquery-rails"
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem "turbolinks"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "jbuilder", "~> 2.0"
# bundle exec rake doc:rails generates the API under doc/api.
gem "sdoc", "~> 0.4.0",          group: :doc

# Use ActiveModel has_secure_password
# gem "bcrypt", "~> 3.1.7"

# Use unicorn as the app server
# gem "unicorn"

# Use Capistrano for deployment
# gem "capistrano-rails", group: :development

# Use debugger
# gem "debugger", group: [:development, :test]

# Thoughtbot-inspired gems
group :development do
  gem "spring"
  gem "spring-commands-rspec"
  gem "web-console"
end

group :production do
  gem "pg"
  gem "rails_12factor"
end

group :development, :test do
  gem "sqlite3"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.1.0"
end

