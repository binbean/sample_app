## Generation things
*without default Test::Unit
rails new sample_app --skip-test-unit
*suppress the installation of production gems
bundle install --without production
*configure Rails to use RSpec in place of Test::Unit
rails generate rspec:install
*suppress the genearation of the default RSpec tests
generate controller StaticPages home help --no-test-framework
## Undoing things
*Controller

    $ rails generate controller FooBars baz quux
    $ rails destroy  controller FooBars baz quux

*Model
    
    $ rails generate model Foo bar:string baz:integer
    $ rails destroy model Foo

*Migration
    
    $ rake db:migrate
    $ rake db:rollback
    $ rake db:migrate VERSION=0


