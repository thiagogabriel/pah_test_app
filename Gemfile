source 'https://rubygems.org'
ruby '2.1.3'

gem 'rails',                  '4.1.6'
gem 'puma',                   '2.9.1'
gem 'secure_headers',         '1.3.3'
gem 'jquery-rails',           '3.1.2'
gem 'turbolinks',             '2.3.0'
gem 'jbuilder',               '2.1.3'
gem 'slim-rails',             '2.1.5'
gem 'pg',                     '0.17.1'
gem 'sass-rails',             github: 'rails/sass-rails', ref: '57ec3397ff99655890895df29a7bf3f683410256'
gem 'coffee-rails',           '4.0.1'
gem 'uglifier',               '2.5.3'
gem 'simple_form',            '3.1.0.rc1'
gem 'flutie',                 '2.0.0'
gem 'bourbon',                '4.0.2'
gem 'neat',                   '1.6.0'
gem 'bitters',                '0.10.1'
gem 'refills',                '0.0.2'
gem 'normalize-rails',        '3.0.1'

group :production, :staging do
  gem 'rails_12factor',       '0.0.2'
  gem 'rack-canonical-host',  '0.1.0'
  gem 'rack-timeout',         github: 'kch/rack-timeout', ref: '83ca9f5141c1fdcb626820b1601c406e3a3a560a'
  gem 'newrelic_rpm',         '3.9.4.245'
  gem 'rollbar',              '1.0.1'
end

group :development do
  gem 'spring',               '1.1.3'
  gem 'foreman',              '0.75.0'
  gem 'jumpup',               '0.0.8'
  gem 'jumpup-heroku',        '0.0.5'
  gem 'better_errors',        '2.0.0'
  gem 'binding_of_caller',    '0.7.2'
  gem 'letter_opener',        '1.2.0'
  gem 'bullet',               '4.13.2'
  gem 'quiet_assets',         '1.0.3'
end

group :test do
  gem 'shoulda-matchers',     '2.7.0', require: false
  gem 'simplecov',            '0.9.1', require: false
  gem 'email_spec',           '1.6.0'
  gem 'capybara',             '2.4.3'
  gem 'poltergeist',          '1.5.1'
  gem 'vcr',                  '2.9.3'
  gem 'webmock',              '1.18.0'
  gem 'database_cleaner',     '1.3.0'
end

group :development, :test do
  gem 'rspec-rails',          '3.1.0'
  gem 'factory_girl_rails',   '4.4.1'
  gem 'pry-rails',            '0.3.2'
  gem 'dotenv-rails',         '0.11.1'
  gem 'awesome_print',        '1.2.0'
end
