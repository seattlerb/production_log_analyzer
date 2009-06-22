ENV.delete 'GEM_PATH'

require 'rubygems'
require 'hoe'

p Hoe.plugins

Hoe.spec 'production_log_analyzer' do
  developer 'Eric Hodel', 'drbrain@segment7.net'

  self.rubyforge_name = 'seattlerb'

  extra_deps << ['rails_analyzer_tools', '>= 1.4.0']
end

