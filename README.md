# To dos app

A simple to do app clone of the [TodoMVC](https://todomvc.com/) example apps. This is used as a toy application to pair on when hiring software engineers at Sell with AMI.

## Getting Started
Install Ruby 3.0.2 using your preferred ruby manager:
``` sh
# via ruby
asdf install ruby

# via rbenv
rbenv install
```

Install Node JS 14.17.6 using your preferred manager:
``` sh
# via asdf
asdf install nodejs

# via nvm
nvm install
```

Once Ruby and NodeJS are installed:
```sh
./bin/setup
```

## Testing

Both `rspec` and `minitest` (rails flavor) are configured so feel free to use either framework to write and run tests.

For rspec:

```ruby
bundle exec rspec
```

For minitest:

```
bundle exec rails test
```