# NepaliDateConverter

A ruby library to convert A.D (english) date to B.S (nepali) date and vice versa.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'nepali_date_converter'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install nepali_date_converter

## Usage

Convert A.D to B.S

```ruby
NepaliDateConverter::Convert.to_bs(yyyy, mm, dd)
```

convert B.S to A.D

```ruby
NepaliDateConverter::Convert.to_ad(yyyy, mm, dd)
```

## Gotcha

Right now we are only able to converter nepali date from year range (2000 - 2089).

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/nepali_date_converter. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

