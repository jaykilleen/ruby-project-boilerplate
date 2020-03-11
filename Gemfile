source "https://rubygems.org"
  
ruby '2.7.0'

gem 'rake', '~> 11.2', '>= 11.2.2'
gem 'pg', '>= 0.18', '< 2.0'
gem 'database_cleaner'
gem 'rubyzip'
gem 'net-sftp', '~> 2.1.2'
gem 'listen', '>= 3.0.5', '< 3.2'
gem 'minitest', '~> 5.8', '>= 5.8.4'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development do
  gem 'guard'
  gem 'guard-minitest'
  gem 'pry', git: 'https://github.com/pry/pry.git', ref: '272b3290b5250d28ee82a5ff65aa3b29b825e37b'
  gem 'byebug'
end