source "https://rubygems.org"
git_source(:github) {|repo|"https://github.com/#{repo}.git"}

ruby "2.5.1"
gem "bootsnap", ">= 1.1.0", require: false
gem "coffee-rails", "~> 4.2.2"
gem "jquery-rails", "4.3.1"
gem "jbuilder", "2.7.0"
gem "puma", "3.9.1"
gem "rails", "5.1.6"
gem "sqlite3"
gem "sdoc", ">= 0.4.0", group: :doc
gem "sass-rails", "~> 5.0.6"
gem "turbolinks", "5.0.1"
gem "uglifier", ">= 3.2.0"
group :development, :test do
	gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end
group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end
group :test do
  gem "rails-controller-testing", "1.0.2"
  gem "minitest", "5.11.3"
  gem "minitest-reporters", "1.1.14"
  gem "guard", "2.13.0"
  gem "guard-minitest", "2.4.4"
end

group :production do
  gem "pg", "0.20.0"
end
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
