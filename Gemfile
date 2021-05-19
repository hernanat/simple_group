source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.0"

gem "bitters"
gem "bootsnap", ">= 1.4.2", require: false
gem "bourbon"
gem "commonmarker"
gem "devise"
gem "devise-i18n"
gem "email_validator"
gem "faraday"
gem "friendly_id", "~> 5.2.4"
gem "action_policy", "~> 0.5.5"
gem "haml-rails", "~> 2.0"
gem "jbuilder", "~> 2.7"
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 4.3"
gem "rails", "~> 6.1.1"
gem "sass-rails", ">= 6"
gem "scenic"
gem "simple_form"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 4.0"

group :development, :test do
  gem "bundler-audit"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "haml_lint", require: false
  gem "pry-rails"
  gem "rspec-rails", "~> 4.0.0"
  gem "rubocop", "~> 1.9.0", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "shoulda-matchers"
end

group :development do
  gem "listen", "~> 3.4"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara"
  gem "formulaic"
  gem "rspec_junit_formatter"
  gem "selenium-webdriver"
  gem "webmock"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
