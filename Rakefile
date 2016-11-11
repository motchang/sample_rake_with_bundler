Bundler.require

namespace :sample do

  desc 'sample'
  task :aws_task do |_t, _args|
    p Aws::Credentials.new(ENV['AWS_ES_ACCESS_KEY_ID'], ENV['AWS_ES_SECRET_ACCESS_KEY'])
  end
end
