source "https://rubygems.org"


gem "rake"
gem "git", ">= 1.2.5"
gem "nokogiri", ">= 1.5.10"
gem "github_api"
gem "highline", ">= 1.6.15"
gem "bundler", ">= 1.0"
gem "rdoc"
gem "builder"

group :development do
  gem "yard", ">= 0.8.5"
  gem "bluecloth"
  gem "cucumber", ">= 1.1.4"
  gem "simplecov"
end

group :test do
  gem "timecop"
  gem "activesupport", "~> 3.2.16"
  gem "shoulda"
  gem "mhennemeyer-output_catcher"
  gem "rr", ">= 1.0.4"
  gem "mocha"
  gem "redgreen"
  gem "test-construct"
  gem 'coveralls', :require => false
end

# yo dawg, i herd u lieked jeweler
group :xzibit do
  # steal a page from bundler's gemspec:
  # add this directory as jeweler, in order to bundle exec jeweler and use the current working directory
  gem 'jeweler', :path => '.'
end


group :debug do
end
