source 'https://rubygems.org'

git_source(:github) do |repo_name|
	repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
	"https://github.com/#{repo_name}.git"
end

ruby '2.4.0'
gem 'rails', '~> 5.0.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.5'
gem 'haml'
gem 'simple_form'
gem 'paperclip'
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'cocoon'
gem 'devise'
gem 'bcrypt', '~> 3.1', '>= 3.1.11'
gem 'will_paginate', '~> 3.1', '>= 3.1.5'
gem 'bootstrap-will_paginate', '~> 0.0.10'
gem 'aws-sdk'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development

group :development, :test do
	gem 'better_errors'
  gem 'sqlite3'
end

group :production do
     gem 'pg'
     gem 'rails_12factor'
end
