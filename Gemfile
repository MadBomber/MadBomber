source 'https://rubygems.org'

############################################
# Constrained Libraries

gem 'bcrypt-ruby',    '~> 3.0.0'  # OpenBSD's bcrypt() password hashing algorithm.
gem 'coffee-rails',   '~> 4.0.0'  # CoffeeScript adapter for the Rails asset pipeline.
gem 'jbuilder',       '~> 1.2'    # Create JSON structures via a Builder-style DSL
gem 'rails',          '4.0.0'     # Full-stack web application framework.
gem 'sass-rails',     '~> 4.0.0'  # Sass adapter for the Rails asset pipeline.
gem 'uglifier',       '>= 1.3.0'  # Ruby wrapper for UglifyJS JavaScript compressor

gem 'therubyracer', platforms: :ruby


############################################
# Unconstrained Libraries

gem 'jquery-rails'  # Use jQuery with Rails 3
gem 'pg'            # A Ruby interface to the PostgreSQL RDBMS
gem 'sqlite3'       # This module allows Ruby programs to interface with the SQLite3 database engine (http://www.sqlite.org)
gem 'turbolinks'    # Turbolinks makes following links in your web application faster (use with Rails Asset Pipeline)
gem 'unicorn'       # Rack HTTP server for fast clients and Unix


##############################################
# Documentation tools

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false  # rdoc html with javascript search index.
end


##############################################
# Handy development tools

group :test do
  gem 'rake'  # This rake is bundled with Ruby but required by Travis-CI to be here
end


##############################################
# Handy development tools

group :development do
  gem 'debugger'            # Fast Ruby debugger - base + cli
  gem 'irbtools'            # irbtools happy irb.
  gem 'irbtools-more'       # irbtools-more adds advancded gems like bond or looksee to irbtools.
  gem 'terminal-notifier'   # Send User Notifications on Mac OS X 10.8.
  gem 'travis'
  gem 'ruby_gntp'           # Ruby library for GNTP(Growl Notification Transport Protocol) client
end

