# MegaLotto

A Ruby gem to generate lottery drawings.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'mega_lotto'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mega_lotto

## Usage

```ruby
MegaLotto::Drawing.new.draw #=> [23, 2, 12, 4, 3, 26]

```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/mega_lotto.

