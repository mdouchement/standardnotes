source 'https://rubygems.org'

gem 'rails', '5.0.1'

gem 'mysql2', '>= 0.3.13', '< 0.5'

gem 'rack-cors', :require => 'rack/cors'

gem 'dotenv-rails', '~> 2.1.1'

gem 'standard-file', require: 'standard_file'

gem 'rotp'

gem 'puma' # Move to production group

# Used for 'respond_to' feature
gem 'responders', '~> 2.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'rspec-rails'

  # gem 'standard-file', :path => "~/Desktop/standard_file_gem", require: 'standard_file'

  # Deployment tools
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-passenger', '>= 0.2.0'
  gem 'capistrano-rails'
  gem 'capistrano-rvm'
  gem 'capistrano-sidekiq'
  gem 'capistrano-git-submodule-strategy', '~> 0.1.22'
end
