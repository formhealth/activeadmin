source "https://rubygems.org"

group :development, :test do
  gem 'rake'
  gem 'devise'
  gem 'arbre', github: 'activeadmin/arbre', ref: 'b546d7a10b95001cb7bd1273bbaa55172de77e98'
  gem 'pundit', require: false
  gem 'draper', '~> 4.0'
  gem "rails", "~> 6.0.0"
  gem "webpacker", "~> 5.1"
  gem "formtastic", "~> 4.0.rc1"
end

group :test do
  gem 'apparition'
  gem 'capybara', '~> 3.14'
  gem 'db-query-matchers', '0.10.0'

  gem 'simplecov', '0.17.1', require: false # Test coverage generator. Go to /coverage/ after running tests
  gem 'cucumber-rails', '~> 2.0', require: false
  gem 'cucumber'
  gem 'database_cleaner'
  gem 'jasmine'
  gem 'jasmine-core', '2.99.2' # last release with Ruby 2.2 support.
  gem 'launchy'
  gem 'parallel_tests', '~> 3.0'
  gem 'rails-i18n' # Provides default i18n for many languages
  gem 'rspec-rails'
  gem 'rspec', github: 'rspec/rspec', ref: '3e6c0fb9c9ec68eddd409cfe7b3eb077b390b302'
  gem 'rspec-core', github: 'rspec/rspec-core', ref: '119282ec3dde5295b337322fc53301c32d0bf7ec'
  gem 'rspec-mocks', github: 'rspec/rspec-mocks', ref: '1728885f65b25a9676c5ce54133ef8a1283e2e0d'
  gem 'rspec-support', github: 'rspec/rspec-support', ref: '6553911974ee93855008f8ff41c26cea6652d74d'
  gem 'rspec-expectations', github: 'rspec/rspec-expectations', ref: 'eb1787f0e1a5ec2c2650048ee60a45d4c9738d78'
  gem "sqlite3", "~> 1.4", platform: :mri
end

group :docs do
  gem 'yard'
  gem 'kramdown'
end

gemspec path: "."
