require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :environment do
  require_relative './config/environment'
end

desc 'drop into the Pry console'
task :console => :environment do
  require 'pry'
  Pry.start
end
