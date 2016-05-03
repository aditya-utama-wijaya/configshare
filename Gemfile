source 'https://rubygems.org'
ruby '2.2.3'

gem 'sinatra'
gem 'thin'
gem 'json'
gem 'sequel'
gem 'rbnacl-libsodium'
gem 'tux'
gem 'hirb'

group :development do
	gem 'rerun'
end

group :test do 
	gem 'minitest'
	gem 'rack'
	gem 'rack-test'
	gem 'rake'
end

group :development, :test do
	gem 'sqlite3'
	gem 'config_env'
end

group :production do
	gem 'pg'
end