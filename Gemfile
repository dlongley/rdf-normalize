source "https://rubygems.org"

gemspec

group :debug do
  gem "wirble"
  gem "byebug", platforms: :mri_21
end

group :development, :test do
  gem 'psych', :platforms => [:mri, :rbx]
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubinius', '~> 2.0'
  gem 'json'
end
