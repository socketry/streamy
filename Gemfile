
source "https://rubygems.org"

gem "utopia", "~> 2.5.0"
# gem "utopia-gallery"
# gem "utopia-analytics"

gem "rake"
gem "bundler"

gem "rack-freeze", "~> 1.2"

gem "relaxo-model"
gem "bcrypt"

group :development do
	gem "falcon", "~> 0.18.14"
	# For `rake server`:
	gem "guard-falcon", require: false
	gem 'guard-rspec', require: false
	
	# For `rake console`:
	gem "pry"
	gem "rack-test"
	
	# For `rspec` testing:
	gem "rspec"
	gem "simplecov"
end

group :production do
	# Used for passenger-config to restart server after deployment:
	gem "passenger"
end
