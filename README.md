# payment

TODO: Write a description here

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  payment:
    github: [your-github-name]/payment
```

## Usage

```crystal
require "payment"
# Excel PMT function: =PMT((9.3/100)/12,36,-12995,6000,0)
puts Payment.calculate(12995.0, 6000.0, 9.3, 36, 0)
```

TODO: Write usage instructions here

## Development

TODO: Write development instructions here

## Contributing

1. Fork it ( https://github.com/[your-github-name]/payment/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [[your-github-name]](https://github.com/[your-github-name]) ed - creator, maintainer
