source 'https://rubygems.org'

ruby '2.3.1'

gem 'activeadmin', '1.0.0'
gem 'delayed_job_active_record', '~> 4.1.2'
gem 'devise'
gem 'rails', '4.2.10'
gem 'unicorn'
gem 'mysql2', '~> 0.3.18'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 4.2.2'
  gem 'sass-rails',   '~> 5.0.7'
  gem 'uglifier'
end

group :development, :test do
  gem 'pry'
  gem 'rspec-rails', '3.4.2'
  gem 'rspec-mocks', '3.4.1'
  gem 'test-unit', '~> 3.0'
  gem "dotenv-rails"
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

group :production do
  gem 'rails_12factor'
  gem 'pg'
  gem 'rails_serve_static_assets'
end
