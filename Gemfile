require "rbconfig"
HOST_OS = RbConfig::CONFIG["host_os"]

source :rubygems

gem "rails", "3.2.11"
gem 'nokogiri'
gem "pg"
gem "puma"
gem "rails_setup"
gem "devise"
gem "strong_parameters"
gem 'cocoon'


group :assets do
  gem "sass-rails"
  gem "coffee-rails"
  gem "bootstrap-sass"
  gem "uglifier"
end

gem "jquery-rails"
gem "haml-rails"
gem "bourbon"
gem "simple_form"
gem "attr_encryptor"
gem "decent_exposure"

group :development, :test do
  gem "cucumber-rails", :require => false
  gem "capybara"
  gem "database_cleaner"
  gem "shoulda"
  gem "launchy"
  gem "factory_girl_rails"
  gem "rspec-rails", '~> 2.12'
  gem 'faker'
  gem "pry-rails"
  gem "rb-fsevent", :require => RUBY_PLATFORM.include?("darwin") && "rb-fsevent"
  gem "ruby_gntp",  :require => RUBY_PLATFORM.include?("darwin") && "ruby_gntp"
  gem "libnotify",  :require => RUBY_PLATFORM.include?("linux")  && "libnotify"
  gem "rb-inotify", :require => RUBY_PLATFORM.include?("linux")  && "rb-inotify"

  gem "rb-fchange",   :platform => :mswin
  gem "win32console", :platform => :mswin
  gem "rb-notifu",    :platform => :mswin
  gem "better_errors"
  gem 'binding_of_caller'
  gem 'meta_request', '0.2.1'
  gem "guard-livereload"
  gem "yajl-ruby"
  gem "rack-livereload"
  gem "guard-cucumber"
  gem "guard-rspec"
  gem "timecop"
  gem "sqlite3"
  gem "foreman"
  gem "zeus"
  gem 'spork', '~> 1.0rc'
end

