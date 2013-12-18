*without default Test::Unit
rails new sample_app --skip-test-unit
*suppress the installation of production gems
bundle install --without production
*configure Rails to use RSpec in place of Test::Unit
rails generate rspec:install

