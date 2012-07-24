require 'rubygems'
require 'bundler'
Bundler.setup
require 'jekyll/epub/tasks'
Jekyll::Epub::Tasks.new do
  web :serve_port, 4000
  epub :destination, "_epub"
end
