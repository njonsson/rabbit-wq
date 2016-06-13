source 'https://rubygems.org'

gemspec

group :debug do
  gem   'pry-byebug',   '~> 3',                 platforms: [:mri_20,
                                                            :mri_21,
                                                            :mri_22]
  gem   'pry-debugger', '~> 0',                 platforms: :mri_19
end

group :doc do
  gem   'yard',         '~> 0', require: false
  gem   'rdiscount',    '~> 2', require: false
end

group :tooling do
  # The Guard RSpec plugin crashes with:
  #
  #     celluloid-0.17.3/lib/celluloid/calls.rb:48:in `check': wrong number of arguments (2 for 1) (ArgumentError)
=begin
  gem   'guard-rspec',  '~> 4', require: false
  if RUBY_PLATFORM =~ /darwin/i
    gem 'rb-fsevent',   '~> 0', require: false
  end
=end
end
