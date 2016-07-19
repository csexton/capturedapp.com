require "rubygems"
require "rake"

desc "Deploy to codeography.com"
task :deploy do
  sh "jekyll build"
  sh "rsync -az --force --delete --progress --exclude-from=.rsyncignore ./_site/ capturedapp.com:capturedapp.com/"
end

