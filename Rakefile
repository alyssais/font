task :default => [:install]

def install_path
  ENV['PREFIX'] ? '$PREFIX/font' : '/usr/local/bin/font'
end

task :install do |t|
  `gem install bundler`
  `bundle`
  
  `cp font #{install_path}`
end

task :uninstall do |t|
  `rm #{install_path}`
end