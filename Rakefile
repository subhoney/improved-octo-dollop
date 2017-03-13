# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Rails.application.load_tasks

desc 'run the rails server'
task :run do 
   sh 'rails server -b $IP -p $PORT'
end

desc 'run test suite'
task :tall do 
    sh 'bundle exec rake test'
end