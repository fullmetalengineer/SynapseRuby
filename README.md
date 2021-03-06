# SynapseRuby
![Gem](https://img.shields.io/gem/v/synapseruby.svg)
![status](https://img.shields.io/badge/status-beta-yellow.svg)

Native API library for SynapseFI REST v3.x

Not all API endpoints are supported.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'synapseruby'
```

And then execute:

```bash
$ bundle
```

Or install it yourself by executing:

```bash
$ gem install synapseruby
```
## Documentation

- [API docs](http://docs.synapsefi.com/v3.1)
- [synapseruby gem docs](https://rubygems.org/gems/synapseruby)
- [Samples demonstrating common operations](samples.md)

## Contributing

For minor issues, please open a pull request. For larger changes or features, please email hello@synapsepay.com. Please document and test any public constants/methods.

## Running the Test Suite

If you haven't already, set the `TEST_CLIENT_ID` and `TEST_CLIENT_SECRET` environment variables in `.env` file .
Please read and update test files with your user own test id's

To run all tests, execute:

```bash
rake test
```

## License

[MIT License](LICENSE)


