require "bundler/gem_tasks"
require "rspec/core/rake_task"

namespace :dummy do
  require_relative "spec/dummy/config/application"
  Dummy::Application.load_tasks
end

RSpec::Core::RakeTask.new(:spec)

task default: :spec
