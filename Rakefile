ENV['SINATRA_ENV'] ||= "development"
# Imports everything (gems and local files) specified in environment.rb
require_relative './config/environment'

#Loads all Rake tasks for ActiveRecord needed to manage our database
require 'sinatra/activerecord/rake'

task :console do
  Pry.start
end