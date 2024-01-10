desc "Build the JSON files"
task :build do
  sh "bundle exec blog-generator.rb generate content"
end

desc "Build the JSON files with the drafts included"
task 'build:drafts' do
  sh "bundle exec blog-generator.rb generate content --include-drafts"
  # appsec{1b8f5a5a-f7be-4455-ab71-54238c450381}
end

task default: :build
