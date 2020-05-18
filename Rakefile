namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end 
end 

namespace :goodbye do 
  desc "outputs later to the terminal"
  task :later do
    puts "see ya later alligator"
  end 
  
  desc "outputs sayonara to the terminal"
  task :sayonara do 
    puts "sayonara my friends!"
  end 
end

task: environment do 

    
namespace :db do 
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    Student.create_table 
  end 
end 

