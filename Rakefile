require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('monday', '0.1.0') do |p|
  p.description     = "Practice create a gem"
  p.url             = "http://github.com/ancv/monday"
  p.author          = "An Cao-Van"
  p.email           = "ancv.it@gmail.com"
  p.ignore_pattern  = ["tmp/*", "script/*"]
  p.development_dependencies = []
end
Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
