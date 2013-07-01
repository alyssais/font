task :default => [:install]

def install_path
  (ENV['PREFIX'] || '/usr/local/bin') + '/font'
end

task :install do |t|
  `gem install bundler`
  `bundle`
  
  FileUtils.cp "font", install_path
end

task :uninstall do |t|  
  FileUtils.rm [install_path]
end