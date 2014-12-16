source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.4'

# Use postgresql as the database for Active Record
gem 'pg'

# Add factory girl
gem 'factory_girl_rails'

# convert wav files to mp3
gem 'paperclip-wav-mp3', '~> 0.0'

# user paperclip to upload new samples
gem "paperclip", :git => "git://github.com/thoughtbot/paperclip.git"

# allows paperclip uploads to be saved to dropbox
gem "paperclip-dropbox", ">= 1.1.7"

group :production do

	#gem for heroku to handle assets 
	gem 'rails_12factor', '0.0.2'

end

group :development, :test do

  #add in the gem for rspec
  gem 'rspec-rails', '~> 3.0.0'

   #add validation-association matchers
  gem 'shoulda-matchers', require: false

  #CAPYBARA SUPER STAR POWERS ADDED
  gem 'capybara'
  
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.2'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
