#require "bundler/gem_tasks"
require 'geminabox-release'
GeminaboxRelease.patch(:host => "http://gems.moviepilot.com:8081")

require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec)

task :default => :spec
