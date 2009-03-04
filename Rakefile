require 'rubygems'
require 'echoe'

msg = File.read("Message")

Echoe.new('nokogirl') do |p|
  p.version = "1.0"
  p.author = ['Aaron Patterson', 'Mike Dalessio']
  p.email = %w{aaronp@rubyforge.org mike.dalessio@gmail.com}
  p.runtime_dependencies = ['nokogiri']
  p.install_message = [$/+%+*+*msg.length+$/]*2*msg+$/

  p.project = "dojo"
  p.need_tar_gz = false
  p.has_rdoc = false
end