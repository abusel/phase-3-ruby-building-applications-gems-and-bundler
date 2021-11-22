# frozen_string_literal: true


git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

source "https://rubygems.org"
gem "rspec"
gem "rest-client"

group :development do
  gem "pry"
  gem "hashie"
  gem "sinatra", "2.0.2"
  gem "octokit", "~> 2.0"
  gem "awesome_print", git: "git@github.com:awesome-print/awesome_print.git"
end

group :test do
    gem "rspec"
end

# gem "rails"
