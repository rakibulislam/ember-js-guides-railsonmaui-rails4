source 'https://rubygems.org'

#specify ruby version to enable the deploy to Heroku instance.
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.rc1'

# Use the 'puma' web server
gem 'puma'

gem 'ember-rails', github: 'emberjs/ember-rails'
# ember-source mentioned in ember-rails readme, but doesn't seem necessary in Gemfile
gem 'ember-source', '1.0.0.rc4' # or the version you need
# Next line is required as of 6/7/2013
gem 'handlebars-source', '1.0.0.rc4' # or the version you need

# Use sqlite3 as the database for Active Record
#gem 'sqlite3'

# Heroku Deployment
group :production do
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
  gem 'rails_log_stdout',           github: 'heroku/rails_log_stdout'
end
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0.rc1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
gem 'coffee-rails-source-maps', group: :development
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

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
