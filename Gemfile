source 'https://rubygems.org'

gemspec

# This are needed here by travis-ci
group :test do
  gem "rake"
  gem "rspec"
end

group :development do
  gem "rb-fchange", require: false
  gem "rb-fsevent", require: false
  gem "rb-inotify", require: false
  gem "ruby_gntp"
  gem "terminal-notifier-guard"
  gem "guard-bundler"
  gem "guard-rspec"
  gem "pry"
  gem "pry-debugger", platforms: :ruby_19
end
