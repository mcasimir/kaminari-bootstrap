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
  gem.name = "kaminari-bootstrap"
  gem.homepage = "http://github.com/mcasimir/kaminari-bootstrap"
  gem.license = "MIT"
  gem.summary = %Q{Kaminari views for Twitter Bootstrap (rails engine)}
  gem.description = %Q{Kaminari views for Twitter Bootstrap (rails engine)}
  gem.email = "maurizio.cas@gmail.com"
  gem.authors = ["mcasimir"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new