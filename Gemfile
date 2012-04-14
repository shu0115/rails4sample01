source 'https://rubygems.org'

# Bundle edge Rails instead:
gem 'rails', :git => 'git://github.com/rails/rails.git'

# 2012/04/14 Add
gem 'active_record_deprecated_finders', :git => 'git://github.com/rails/active_record_deprecated_finders.git'

group :development, :test do
  gem 'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sprockets-rails', :git => 'git://github.com/rails/sprockets-rails.git'

#  gem 'sass-rails',   '~> 3.2.3'
#  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# ----- Add ----- #
# For Heroku
group :production do
  gem 'pg'
end

gem 'thin'

# Utility
gem 'kaminari'
gem 'html5_validators'
gem 'active_decorator'

# OmniAuth
gem 'omniauth-github'
gem 'omniauth-twitter'
# ----- / Add ----- #
