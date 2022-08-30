source "https://rubygems.org"
ruby File.read(File.expand_path("../.ruby-version", __FILE__)).strip

# Static site generator
gem "activesupport", "~> 6.1" # middleman 4.4.3-pre allows us to use activesupport 7.x but stay with 6.1 at this moment
## See https://github.com/middleman/middleman/pull/2566
gem "middleman", github: "tnir/middleman", branch: "4.x-backport-936d19c"
## Extensions
gem "middleman-blog"
gem "middleman-search", github: "deivid-rodriguez/middleman-search", branch: "workarea-commerce-master"
gem "middleman-syntax"

## Template engines
gem "builder"
gem "haml", "~> 5.2.2"
gem "kramdown"

# Rake tasks
gem "rake"
## To retrieve a list of contributors from GitHub
gem "octokit", "~> 5.3"
## To generate ERB files from ronn files from rubygems/rubygems
gem "ronn"
## To strip (man:strip_pages)
gem "nokogiri", "~> 1.13"

group :development do
  gem "pry"
  gem "pry-byebug"

  gem "haml_lint", "~> 0.40"
  gem "rubocop"
end
