source "https://rubygems.org"

gem "rails", "5.1.4"
gem "mysql2"
gem "sass-rails" # Use SCSS for stylesheets
gem "uglifier" # Use Uglifier as compressor for JavaScript assets
gem "coffee-rails" # Use CoffeeScript for .js.coffee assets and views
gem "jquery-rails" # Use jquery as the JavaScript library
gem "httparty" # API calls
gem "devise" # authenitcation
gem 'devise_masquerade'
gem "paperclip" # file attachments
gem "ckeditor" # html editor
gem "websocket" # connect to websocket - for healthcheck
gem "gitlab" # gitlab api
gem "diffy" # diff strings
gem "newrelic_rpm" # monitoring
gem "sentry-raven" # error monitoring
gem "dotenv" # environment variables from a file
gem "snmp" # snmp checking
gem "google-api-client", "0.9.pre5" # google apis
gem "analytics-ruby", :require => "segment/analytics" # segment.io
gem "aws-sdk" # aws connection
gem "kaminari" # pagination
gem "ruby-saml" # single sign on standard
gem "attr_encrypted" # encrypt columns
gem "pusher" # multi-user
gem "saml_idp"
gem "rails_server_timings"

gem 'sidekiq'
gem 'sidekiq-failures'

gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'

group :test, :development do # build testing
  gem "awesome_print", require: "ap" # pretty print ruby objects in console (helps w/ reading big hashes, arrays, etc.)
  gem "pry"
end

group :development do
  gem "bullet" # check for n+1 queries
  gem "better_errors"
  gem "binding_of_caller"
  gem "meta_request"
  gem "rubocop", require: false
end

group :test do
  gem "rspec-rails"
  gem "factory_girl_rails"
  gem "faker"
  gem "database_cleaner"
  gem "simplecov", :require => false # code coverage analysis
  gem "cucumber-rails", :require => false # behavioral testing
  gem "selenium-webdriver" # browser automation for behavioral testing
  gem "rails-controller-testing"
end

group :production, :staging do
  gem "exception_notification" # send emails for exceptions
end
