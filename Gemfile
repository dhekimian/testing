source 'https://rubygems.org'

gem 'analytics-ruby', require: 'segment/analytics' # segment.io
gem 'attr_encrypted' # encrypt columns
gem 'aws-sdk' # aws connection
gem 'ckeditor' # html editor
gem 'coffee-rails' # Use CoffeeScript for .js.coffee assets and views
gem 'devise' # authenitcation
gem 'devise_masquerade'
gem 'diffy' # diff strings
gem 'dotenv' # environment variables from a file
gem 'einhorn' # this enables us to perform rolling updates for sidekiq
gem 'gitlab' # gitlab api
gem 'google-api-client', '0.9.pre5' # google apis
gem 'httparty' # API calls
gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'kaminari' # pagination
gem 'mysql2'
gem 'newrelic_rpm' # monitoring
gem 'paperclip' # file attachments
gem 'pusher' # multi-user
gem 'rails', '5.1.4'
gem 'rails_server_timings'
gem 'ruby-saml' # single sign on standard
gem 'saml_idp'
gem 'sass-rails' # Use SCSS for stylesheets
gem 'sidekiq'
gem 'sidekiq-failures'
gem 'snmp' # snmp checking
gem 'uglifier' # Use Uglifier as compressor for JavaScript assets
gem 'webpacker', '~> 3.4'
gem 'websocket' # connect to websocket - for healthcheck
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'

group :test, :development do # build testing
  gem 'awesome_print', require: 'ap' # pretty print ruby objects in console (helps w/ reading big hashes, arrays, etc.)
  gem 'pry'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet' # check for n+1 queries
  gem 'meta_request'
  gem 'rubocop', require: false
end

group :test do
  gem 'cucumber-rails', :require => false # behavioral testing
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'selenium-webdriver' # browser automation for behavioral testing
  gem 'simplecov', :require => false # code coverage analysis
end

group :production, :staging do
  gem 'exception_notification' # send emails for exceptions
  gem 'sentry-raven' # error monitoring
end
