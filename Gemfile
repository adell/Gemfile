# encoding: UTF-8

# @since 0.0.1
# @version 0.0.1
# @author Ademir Lima - adellima@gmail.com

source 'http://gemcutter.org'
source 'http://rubygems.org'

# Application
# ===========

gem 'rails', '3.2.13'
gem 'rake', '10.0.4'
gem 'mysql2'
gem 'jquery-rails'
 
gem 'therubyracer'

gem 'dynamic_form', '1.1.4'
gem 'decent_exposure'
gem 'will_paginate', "~> 3.0.pre2"
gem 'pdfkit'

gem 'web-app-theme', '~> 0.8.0'

# Easily include static pages in your Rails app (like About us and other)
# gem 'high_voltage'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# MailChimp Email Markup Layouts
# https://github.com/mailchimp/Email-Blueprints

# Addressable is a replacement for the URI implementation that is part of Ruby's standard library
# gem 'addressable'

# ClientSideValidations for Ruby on Rails and integration with simple_form
# https://github.com/dockyard/client_side_validations-simple_form/wiki/Validations-with-simple_form-Twitter-Bootstrap-integration
# gem 'client_side_validations'
# gem 'client_side_validations-simple_form'

# Your Rails variables in your JS
# gem 'gon'

# File upload
# gem "paperclip", "~> 3.0"
# gem 'carrierwave'

# HTTP
# ====

gem 'httparty', '0.11.0'
gem 'browser', '0.1.6'


# Background tasks
# ================

gem 'resque', '1.24.1'
gem 'resque_mailer', '2.2.4'
gem 'resque-lock-timeout', '0.4.1'


# Search
# ======

gem 'tire', '0.5.7'


# Authentication
# ==============

gem 'devise', '2.2.4'

# Authorization Gem for Ruby on Rails
gem 'cancan'


# Errors
# ======

gem 'sentry-raven', '0.4.6'


# Views/Templates
# ===============

gem 'oj', '2.0.12'
gem 'mustache', '0.99.4'
gem 'stache', '0.9.1'
gem 'yard', '0.8.6.1'
gem 'simple_form'


# Utils
# =====

gem 'radix62', '1.0.1'


# Deployment
# ==========

#gem 'capistrano', '2.15.4'
#gem 'god', '0.13.2'


# Production
# ==========

group :production do

  # Server
  # ------

  gem 'unicorn', '4.6.2'
  gem 'unicorn-rails', '1.0.1'
  gem 'capistrano-unicorn', '0.1.7', :require => false

  # Allows you to easily perform backup operations
  gem 'backup', require: false

end


# Development
# ===========

group :development do

  gem 'thin', '1.5.1'

  # Better error page for Rails and other Rack apps
  gem 'better_errors'

end


# Test
# ====

group :test do

  gem 'rspec-rails', '2.13.2'
  gem 'factory_girl_rails', '4.2.1'
  gem 'database_cleaner', '1.0.1'
  gem 'shoulda', '3.5.0'
  gem 'resque_spec', '0.13.0'

  gem 'autotest', '4.4.6'
  gem 'autotest-rails', '4.1.2'

end
