require 'rspec/core/rake_task'

task :tests => [:spec]

desc 'Task para execução dos specs'
RSpec::Core::RakeTask.new do |t|
  t.pattern = 'spec/*_test.rb'
  t.verbose = false
end