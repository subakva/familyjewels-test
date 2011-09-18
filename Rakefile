# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "t"
  gem.homepage = "http://github.com/subakva/family-jewels-test"
  gem.license = "MIT"
  gem.summary = %Q{A repo/gem for testing family jewels}
  gem.description = %Q{A repository/gem for testing family jewels}
  gem.email = "jdwadsworth@gmail.com"
  gem.authors = ["Jason Wadsworth"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new
