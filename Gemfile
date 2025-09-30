source "http://rubygems.org"

gem "rake"
gem "sinatra", ">= 2.0.0"
gem "dm-core"
gem "dm-serializer"
gem "dm-migrations"
gem "dm-validations"
gem "dm-timestamps"
gem "heroku"
gem "httparty"
gem "fastercsv"

group :production do
  gem "pg"
  gem "dm-postgres-adapter"
end

group :development do
  gem "sqlite3-ruby"
  gem "dm-sqlite-adapter"
  gem "shotgun", ">= 0.9.1"
end

