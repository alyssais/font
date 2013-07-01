task :default => [:install]

task :install do |t|
  `gem install bundler`
  `bundle`
  
  if ENV['PREFIX']
    `cp font $PREFIX/font`
  else
    `cp font /usr/local/bin/font`
  end
end