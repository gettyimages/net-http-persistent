# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugin :git
Hoe.plugin :minitest
Hoe.plugin :travis

Hoe.spec 'net-http-persistent-pool' do
  developer 'Getty Images', 'opensource@gettyimages.com'

  self.readme_file      = 'README.rdoc'
  self.extra_rdoc_files += Dir['*.rdoc']

  license 'MIT'

  rdoc_locations <<
    'docs.seattlerb.org:/data/www/docs.seattlerb.org/net-http-persistent/'

  dependency 'connection_pool', '~> 2.1'
  dependency 'minitest',        '~> 5.2', :development
end

# vim: syntax=Ruby
