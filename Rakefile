require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |t|
  t.fail_on_error = true
  t.pattern = 'spec/**/*_spec.rb'
end

task default: [:spec]