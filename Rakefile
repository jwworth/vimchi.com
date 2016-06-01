require 'dotenv'
Dotenv.load

desc "Deploy site"
task :deploy do
  sh "middleman build --clean"
  sh "rsync -av --no-p --chmod=+r -e ssh --delete build/ #{ENV['DEPLOY_TARGET']}"
end
