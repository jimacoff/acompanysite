source 'https://rubygems.org'

ruby "2.0.0"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.beta1'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 4.0.0.beta1'
  gem 'coffee-rails', '~> 4.0.0.beta1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'

  gem 'bootstrap-sass'
  gem 'formtastic-bootstrap'
  gem 'bootstrap-datepicker-rails'

  gem 'formtastic'

  gem 'haml'
  gem 'haml-rails'


end

gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', group: :development

# To use debugger
# gem 'debugger'

gem 'devise'
gem 'figaro'

group :development, :test do
  gem 'rspec-rails'
  gem 'sqlite3'
  gem 'puma'

  gem 'factory_girl_rails'

  gem 'quiet_assets'

  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'cucumber-rails'
  gem 'launchy'
  gem 'capybara'
end

#group :production do
#  gem 'pg'
#end