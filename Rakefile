require "rubygems"
require "rake"

desc "Deploy to codeography.com"
task :deploy do
  sh "jekyll build"
  sh "scp -r _site/* capturedapp.com:capturedapp.com/"
end

