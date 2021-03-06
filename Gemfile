source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'bootsnap', '>= 1.4.2', require: false # Reduces boot times through caching; required in config/boot.rb
gem 'carrierwave', '~> 2.1' # Upload files in your Ruby applications, map them to a range of ORMs, store them on different backends.
gem 'devise', '~> 4.7', '>= 4.7.3' # Flexible authentication solution for Rails with Warden
gem 'jbuilder', '~> 2.7' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'mini_magick', '~> 4.10', '>= 4.10.1' # Manipulate images with minimal use of memory via ImageMagick / GraphicsMagick
gem 'puma', '~> 4.1' # Use Puma as the app server
gem 'rails', '~> 6.0.3', '>= 6.0.3.3' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'sass-rails', '>= 6' # Use SCSS for stylesheets
gem 'sqlite3', '~> 1.4' # Use sqlite3 as the database for Active Record
gem 'turbolinks', '~> 5' # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'webpacker', '~> 4.0' # Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
# gem 'bcrypt', '~> 3.1.7' # Use Active Model has_secure_password
# gem 'redis', '~> 4.0' # Use Redis adapter to run Action Cable in production
# gem 'image_processing', '~> 1.2' # Use Active Storage variant

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw] # Call 'byebug' anywhere in the code to stop execution and get a debugger console
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0' # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
end

group :test do
  gem 'capybara', '>= 2.15' # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  gem 'webdrivers' # Easy installation and use of web drivers to run system tests with browsers
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
