source "http://rubygems.org"

gemspec path: __dir__

# Uncomment and change rails version for testing purposes
# gem "rails", "~> 5.2.0"
# gem "rails", "~> 6.0.0"
# gem "rails", "~> 6.1.0"
# gem "rails", "~> 7.0.1"
# gem "rails", git: "https://github.com/rails/rails.git", branch: "main"

group :development do
  gem "chandler", ">= 0.7.0"
  gem "htmlbeautifier"
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "webpacker"
end

group :test do
  gem "diffy"
  gem "equivalent-xml"
  gem "mocha"
  gem "sqlite3"
end

group :ci do
  gem "danger"
end
