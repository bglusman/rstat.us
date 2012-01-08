source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Asset template engines
gem 'compass', :git => "git://github.com/chriseppstein/compass.git", :branch => "rails31"
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'sunspot_mongo_mapper'
gem "haml-rails"
gem 'jquery-rails'

gem 'unicorn'
gem 'omniauth', :git => 'git://github.com/intridea/omniauth.git'
gem "sinatra", :require => "sinatra/base"
gem "mongo_mapper"
gem "bson_ext"
gem "i18n"
gem "twitter"
gem "pony"
gem "bcrypt-ruby", :require => "bcrypt"
gem "rdiscount"
gem "ostatus", "~>0.0.9"
gem "osub", "~>0.0.6"
gem "opub"
gem "redfinger"
gem "nokogiri"
gem "tzinfo"
gem "rsa"
gem "exceptional"

# background job queue
gem "delayed_job", :git => "git://github.com/collectiveidea/delayed_job.git", :tag => "v2.1.4"
gem "delayed_job_mongo_mapper", :git => "git://github.com/earbits/delayed_job_mongo_mapper.git"
gem "whenever"

group :development, :test do
  gem 'sunspot_rails', :git => 'https://github.com/sunspot/sunspot.git', :ref => '79175ea'
  #gem 'sunspot_solr', :git => 'https://github.com/sunspot/sunspot', :ref => '79175ea'
  gem 'sunspot_solr', :git => 'https://github.com/sunspot/sunspot', :ref => 'ada19e5'
  # as per http://stackoverflow.com/questions/8152951/solr-connection-refused-error-after-java-update-on-mac-os-x-lion
  gem 'rack-test'
  gem "database_cleaner"
  gem "factory_girl"
  gem "capybara"
  gem "rocco"
  gem "pygmentize"
  gem "mocha"
  gem "vcr"
  gem "simplecov", "~> 0.4.0", :require => false
  gem "launchy"
end

group :test do
  gem "webmock"
  #gem "sunspot_matchers"
  #gem "sunspot-rails-tester"
end
