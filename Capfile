# Load DSL and set up stages
require 'capistrano/setup'
require 'new_relic/recipes'

# Include default deployment tasks
require 'capistrano/deploy'

require 'capistrano/rails'
require 'capistrano/gitflow'
require 'capistrano/faster_assets'

# Include tasks from other gems included in your Gemfile
#
# For documentation on these, see for example:
#
#   https://github.com/capistrano/rvm
#   https://github.com/capistrano/rbenv
#   https://github.com/capistrano/chruby
#   https://github.com/capistrano/bundler
#   https://github.com/capistrano/rails
#   https://github.com/capistrano/passenger
#
# require 'capistrano/rvm'
require 'capistrano/rbenv'
set :rbenv_type, :user
set :rbenv_ruby, '2.1.5'
# require 'capistrano/chruby'
require 'capistrano/bundler'
# require 'capistrano/rails/assets'
# require 'capistrano/rails/migrations'
# require 'capistrano/passenger'

# Load custom tasks from `lib/capistrano/tasks' if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
