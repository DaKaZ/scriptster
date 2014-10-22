# Scriptster

A small library to make your scripts hip ;-).

## Installation

Add this line to your application's Gemfile:

    gem 'scriptster'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install scriptster

## Usage

TODO: Write usage instructions here

```ruby
require 'scriptster'

Scriptster::configure do |conf|
  conf[:name] = "my-script"
end

Scriptster::log :info, "Starting ..."

Scriptster::ShellCmd.new "git branch",
  :show_out = true,
  :show_err = true,
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/scriptster/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
