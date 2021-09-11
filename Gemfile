# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", github: "rails/rails", branch: "6-1-stable"
#gem "rails", "6.1.1"

gem "mysql2"
gem "nokogiri"
gem "rack-contrib", require: false
gem "faraday", require: false

# change to stable version after https://github.com/rails/sprockets/pull/660
gem "sprockets"#, github: "rails/sprockets"
gem "sprockets-rails"#, github: "rails/sprockets-rails"
gem "warning"

gem "rails-observers", github: "rails/rails-observers"
gem "htmlentities"
gem "will_paginate", github: "kvokka/will_paginate", branch: "fix-page_entries_info"
gem "rack-utf8_sanitizer"

gem "sentry-ruby"
gem "sentry-rails"
gem "sentry-sidekiq"

gem "net-ssh"
gem "net-scp"
gem "cancancan", require: false
gem "sitemap_generator"
gem "mini_magick"
gem "dalli"
gem "kgio"
gem "RedCloth"
gem "jbuilder"

gem "parallel", require: false

gem "thinking-sphinx"
gem "progress_bar"
gem "roman-numerals", require: false

# still uses by contents/suggests
gem "bitmask_attributes", github: "joelmoss/bitmask_attributes", require: false


gem "sidekiq"

gem "streamio-ffmpeg", github: "madmax/streamio-ffmpeg"
gem "cocaine"
gem "unicode"

gem "mechanize", require: false
# for foregin keys
# gem "immigrant"
gem "koala", "~> 3.0", require: false
gem "whenever", require: false
gem "truncate_html", github: "hgmnz/truncate_html", require: false
gem "god", require: false
gem "oink"

gem "xan_markup", github: "madmax/xan_markup"
gem "rails_autolink"

gem "simple_memoize"

gem "pry-rails"

gem "sassc-rails"
gem "sassc"
gem "coffee-rails"

gem "uglifier"

# javascripts
gem "jquery-rails"
gem "eco"
gem "select2-rails"
gem "jquery-fileupload-rails"
gem "bootstrap-datepicker-rails"
gem "autoprefixer-rails"

gem "chartkick"
gem "uri-js-rails"

gem "unicorn", require: false
gem "puma", require: false
gem "bootsnap"

group :development, :test do
  gem "web-console"
  gem "byebug"
  gem "pry-byebug"
  gem "ruby-prof"
  gem "pry-doc"

  gem "rack-mini-profiler", require: false

  # For call-stack profiling flamegraphs
  gem "flamegraph"
  gem "stackprof"

  gem "listen"
  gem "vcr"
  gem "webmock"
end

gem "newrelic_rpm"

group :test do
  gem 'capybara'
  gem 'cuprite'
end

gem "memory_profiler"
gem "counter_culture"
gem "fuzzy_match", require: false

# rails 4.2 extractions
gem "responders"

gem "rack-cors", require: "rack/cors"
gem "pickup", require: false

gem "twitter", require: false
gem "yt"
gem "google-oauth2-installed"

# rss
gem "feedjira"

gem "lazy_object"
gem "webpacker"

gem "slack-notifier"
gem "geoip"

# detect if request is made by bod
gem "voight_kampff"

gem "premailer-rails"
gem "truemail"
gem "validate_url", github: "perfectline/validates_url"

# remove when they release after they release new version with ruby 3.0 support
gem "net-http-persistent", github: "tricknotes/net-http-persistent", branch: "gemspec"
gem "json-ld"
gem "addressable"
