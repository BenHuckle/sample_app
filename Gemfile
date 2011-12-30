source 'http://rubygems.org'

gem 'rails', '3.1.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

group :production do
  gem 'pg'
end
group :development, :test do
  gem 'sqlite3'
end

group :development do
	gem 'rspec-rails', '2.6.1'
	gem "autotest-rails-pure"
  gem "autotest-growl"
  gem "autotest-fsevent"
    gem 'autotest'

end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'spork', '0.9.0.rc8'
  gem "autotest-rails-pure"
  gem "autotest-growl"
  gem "autotest-fsevent"
  gem 'webrat'

end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
