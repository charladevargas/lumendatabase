source 'https://rubygems.org'

gem 'active_model_serializers', '~> 0.8.3'
gem 'activerecord-import'
gem 'acts-as-taggable-on'
gem 'addressable'
gem 'ancestry'
gem 'bootstrap-datepicker-rails', '>= 1.8.0.1'
gem 'cancancan'
# country_select has breaking changes in 2.x:
# https://github.com/stefanpenner/country_select/blob/master/UPGRADING.md
# It also removes CountrySelect::ISO_COUNTRIES_FOR_SELECT in 1.3, which is a
# breaking change for us.
gem 'country_select', '~> 1.2.0'
gem 'coveralls', require: false
gem 'date_validator'
gem 'devise', '>= 4.6.2'
gem 'dotenv-rails', '>= 2.7.2'
gem 'flutie'
gem 'high_voltage'
gem 'html2md', require: false
gem 'jquery-placeholder-rails'
gem 'jquery-rails', '>= 4.3.3'
gem 'jquery-ui-rails', '>= 6.0.1'
# kaminari is locked because we've monkeypatched it to work around
# slow postgres table counts on large tables.
gem 'kaminari', '0.14.1'
gem 'lograge', '>= 0.11.1'
gem 'loofah', '>= 2.2.3'
gem 'mime-types'
gem 'oink'
gem 'paperclip', '~> 5'
gem 'pg', '0.20.0'
gem 'rack', '>= 1.6.11'
# rack-attack 5 has breaking changes that we should deal with later.
gem 'rack-attack', '~> 4.0'
gem 'rack-mini-profiler'
gem 'rails', '~> 5.2.4', '>= 5.2.4.6'
gem 'rails_admin', '>= 1.4.2'
gem 'rails_admin_tag_list', '>= 0.2.0'
# Monkeypatched temporarily for debugging purposes
gem 'recaptcha'
gem 'recipient_interceptor', require: false
gem 'redcarpet'
gem 'select2-rails', '~> 4.0', '>= 4.0.3'
gem 'simple_form', '>= 4.0.0'
gem 'skylight'
gem 'stackprof'
gem 'turnout'

# These need to go last or tests fail.
gem 'elasticsearch-model', '~> 5.0'
gem 'elasticsearch-rails', '~> 5.0'

group :development do
  gem 'bullet'
  gem 'derailed'
  gem 'memory_profiler'
end

group :development, :test do
  gem "factory_bot_rails", ">= 5.0.2"
  gem 'phantomjs'
  gem 'pry', '~> 0.10.4'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-collection_matchers', '~> 1.1', '>= 1.1.2'
  gem 'rspec-rails', '>= 3.6.0'
  gem 'ruby-prof'
  gem 'sham_rack'
end

group :development, :test, :assets do
  gem 'bourbon'
  gem 'coffee-rails', '>= 4.2.2'
  gem 'neat'
  gem 'sass-rails', '>= 5.0.7'
  gem 'therubyracer'
  gem 'uglifier'
end

group :test do
  gem 'curb'
  gem 'database_cleaner'
  gem 'elasticsearch-extensions'
  gem 'fakeweb'
  gem 'poltergeist'
  gem 'rack-test', require: 'rack/test'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.1'
  gem 'simplecov', require: false
  gem 'spork-rails', git: 'https://github.com/sporkrb/spork-rails'
  gem 'timecop'
  gem 'vcr'
  gem 'webmock'
end
