require 'rubygems'
require 'cucumber'
require 'cucumber/rake/task'
require 'allure-cucumber'

Cucumber::Rake::Task.new(:features) do |t|
  sh 'bundle'
  t.profile = 'default'
end

task :default => :features