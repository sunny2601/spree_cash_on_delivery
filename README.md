SpreeCashOnDelivery
===================

Introduction goes here.
	Support 'spree_core' '~> 2.0.0', 'ruby' '~> 1.9.3'
Installation
------------

Add spree_cash_on_delivery to your Gemfile:

```ruby
gem 'spree_cash_on_delivery'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_cash_on_delivery:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_cash_on_delivery/factories'
```

Copyright (c) 2014 [Vishal Zambre], released under the New BSD License
