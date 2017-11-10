require "bundler/gem_tasks"
require "rspec/core/rake_task"

#must establish a connection to db here, 

require "sinatra/activerecord/rake"

require_relative './config/environment'

RSpec::Core::RakeTask.new(:spec)

task :default => :spec
