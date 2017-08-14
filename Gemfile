source 'https://rubygems.org'

ruby '2.4.1'
#ruby-gemset=railstutorial_rails_5_0
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# System gems
gem 'rails', '5.0.5'
gem 'pg', '0.18'
gem 'puma', '3.0'

#Front-end
gem 'sass-rails', '5.0.6'
gem 'uglifier', '1.3.0'

# Use CoffeeScript for .coffee assets // JavaAcript
gem 'coffee-rails', '4.2'
gem 'jquery-rails'
gem 'turbolinks', '5'
gem 'jbuilder', '2.5'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '3.3.0'
  gem 'listen', '3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '2.0.0'
end

group :production do
  gem 'rails_12factor', '0.0.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
