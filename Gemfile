source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails',          '6.0.2.2'
gem 'aws-sdk-s3',     '1.46.0', require: false
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'active_storage_validations'
gem 'image_processing'
gem 'mini_magick'
gem 'bootstrap-will_paginate'
gem 'bootstrap-sass', '3.4.1'
gem 'puma',           '3.12.1'
gem 'sass-rails',     '5.1.0'
gem 'webpacker',      '4.0.7'
gem 'turbolinks',     '5.2.0'
gem 'jbuilder',       '2.9.1'
gem 'bootsnap',       '1.4.4', require: false
gem 'slim-rails'
gem 'html2slim'

group :development, :test do
  gem 'sqlite3', '1.4.1'
  gem 'byebug',  '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'rails-controller-testing'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
  gem 'shoulda-matchers'
end

group :development do
  gem 'web-console',           '4.0.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.1.0'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'capybara',                 '3.28.0'
  gem 'webdrivers'
end

group :production do
  gem 'pg', '1.1.4'
end

# Windows ではタイムゾーン情報用の tzinfo-data gem を含める必要があります
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
