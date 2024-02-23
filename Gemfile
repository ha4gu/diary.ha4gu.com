source "https://rubygems.org"

ruby "3.3.0"

gem "bootsnap", require: false
gem "cssbundling-rails"
gem "image_processing"
gem "jsbundling-rails"
gem "pg"
gem "propshaft"
gem "puma"
gem "rails"
gem "rails-i18n"
gem "stimulus-rails"
gem "turbo-rails"

group :development do
  gem "web-console"
end

group :development, :test do
  gem "debug"
  gem "factory_bot_rails"
  gem "rspec-rails"
end

group :development, :test, :rubocop do
  gem "rubocop-capybara", require: false
  gem "rubocop-factory_bot", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-rubycw", require: false
  gem "standard", "~> 1.34", require: false
end

group :test do
  gem "shoulda-matchers"
end
