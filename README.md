# Qlty Ruby Coverage Example

[Qlty](https://example.com) is a Code Health Platform with support for code coverage.

This repository is an example using Qlty to track code coverage for a Ruby project. Coverage data is generated during the [Rspec](https://rspec.info/) run and then uploaded to Qlty.

This repository uses [Rspec](https://rspec.info/) for testing and [simplecov](https://github.com/simplecov-ruby/simplecov) to generate test coverage.

## Requirements

- Ruby 2.7 or above
- Test run with [bundle exec rspec](https://rspec.info/)
- An account on Qlty (free for open source)
- `QLTY_COVERAGE_TOKEN` is set as an environment variable

## Set up

See [`.circleci/config.yml`](./.circleci/config.yml) in this repository for a basic configuration.

## License

[MIT License](./LICENSE.md)
