source 'https://rubygems.org'
git_source( :github ){|repo| "https://github.com/#{ repo }.git" }

ruby '~> 2.5'

gem 'attr_encrypted' # encrypt columns
gem 'autoprefixer-rails' # Add vendor prefixes to CSS
gem 'aws-sdk-s3' # aws connection
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
gem 'omniauth-rails_csrf_protection'
gem 'paper_trail'
gem 'paper_trail-globalid'
gem 'paperclip' # file attachments
gem 'pundit'
gem 'pusher' # multi-user
gem 'rack-cors', require: 'rack/cors'
gem 'rails', '5.2.3'
gem 'rbvmomi'
gem 'ruby-saml' # single sign on standard
gem 'saml_idp', '0.7.2' # broke gitlab connection going to 0.8.0
gem 'sassc', '2.1.0' # segfault using 2.2.0, & 2.2.1
gem 'sassc-rails' # Use SCSS for stylesheets
gem 'scavenger' # SVG sprite sheets generator
gem 'sidekiq'
gem 'sidekiq-failures'
gem 'snmp' # snmp checking
gem 'uglifier' # Use Uglifier as compressor for JavaScript assets
gem 'webpacker'
gem 'websocket' # connect to websocket - for healthcheck
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'

group :production, :staging do
  gem 'exception_notification' # send emails for exceptions
  gem 'rails_server_timings'
  gem 'sentry-raven' # error monitoring
end

group :staging, :development do
  gem 'flamegraph', platforms: :ruby # required for rack-mini-profiler
  gem 'rack-mini-profiler', require: false
  gem 'stackprof', platforms: :ruby # required for rack-mini-profiler
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet' # check for n+1 queries
  gem 'meta_request'
  gem 'pry-rails'
  gem 'puma'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'web-console'
end

group :development, :test do # build testing
  gem 'awesome_print', require: 'ap' # pretty print ruby objects in console (helps w/ reading big hashes, arrays, etc.)
  gem 'bundler-audit'
  gem 'database_cleaner'
  gem 'pry-byebug'
  gem 'zero-rails_openapi'
end

group :test do
  # gem 'cucumber-rails', :require => false # behavioral testing
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'fuubar'
  gem 'parallel_tests'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'ruumba'
  gem 'simplecov', require: false # code coverage analysis
  gem 'simplecov-lcov', require: false # code coverage analysis format
  gem 'undercover', platforms: :ruby # test coverage analysis
  gem 'webmock' # stubbing http requests
end
