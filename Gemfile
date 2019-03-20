source 'https://rubygems.org'
git_source( :github ){|repo| "https://github.com/#{ repo }.git" }

ruby '~> 2.5.3'

gem 'attr_encrypted' # encrypt columns
gem 'aws-sdk' # aws connection
gem 'bootsnap', require: false
gem 'coffee-rails' # Use CoffeeScript for .js.coffee assets and views
gem 'commonmarker' # markdown parser
gem 'devise' # authenitcation
gem 'devise_masquerade'
gem 'devise_token_auth'
gem 'diffy' # diff strings
gem 'dotenv' # environment variables from a file
gem 'einhorn' # this enables us to perform rolling updates for sidekiq
gem 'gitlab' # gitlab api
gem 'google-api-client', '0.9.pre5' # google apis
gem 'httparty' # API calls
gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'kaminari' # pagination
gem 'mysql2'
gem 'newrelic_rpm'
gem 'omniauth'
gem 'paper_trail'
gem 'paper_trail-globalid'
gem 'paperclip' # file attachments
gem 'pundit'
gem 'pusher' # multi-user
gem 'rails', '5.2.2.1'
gem 'ruby-saml' # single sign on standard
gem 'saml_idp'
gem 'sassc-rails' # Use SCSS for stylesheets
gem 'sidekiq'
gem 'sidekiq-failures'
gem 'snmp' # snmp checking
gem 'uglifier' # Use Uglifier as compressor for JavaScript assets
gem 'webpacker', '~> 3.4'
gem 'websocket' # connect to websocket - for healthcheck
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'

group :production, :staging do
  gem 'exception_notification' # send emails for exceptions
  gem 'rails_server_timings'
  gem 'sentry-raven' # error monitoring
end

group :staging, :development do
  gem 'flamegraph' # required for rack-mini-profiler
  gem 'rack-mini-profiler', require: false
  gem 'stackprof' # required for rack-mini-profiler
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet' # check for n+1 queries
  gem 'meta_request'
  gem 'rubocop', require: false
  gem 'web-console'
end

group :development, :test do # build testing
  gem 'awesome_print', require: 'ap' # pretty print ruby objects in console (helps w/ reading big hashes, arrays, etc.)
  gem 'database_cleaner'
  gem 'pry'
end

group :test do
  # gem 'cucumber-rails', :require => false # behavioral testing
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'fuubar'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'ruumba'
  gem 'selenium-webdriver' # browser automation for behavioral testing
  gem 'simplecov' # code coverage analysis
  gem 'simplecov-lcov' # code coverage analysis format
  gem 'undercover' # test coverage analysis
  gem 'webmock' # stubbing http requests
end
