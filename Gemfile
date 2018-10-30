source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'sdoc', group: :doc
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do

  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'spring'


end


group :production do

  gem 'pg'
  gem 'rails_12factor'

end

group :development do

  gem 'web-console'

end

group :test do

  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest', '2.3.1'

end

