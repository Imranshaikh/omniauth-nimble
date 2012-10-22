# Omniauth::Nimble

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'omniauth-nimble'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install omniauth-nimble

## Usage

**Basic Usage**

    use OmniAuth::Builder do
      provider :nimble, ENV['NIMBLE_KEY'], ENV['NIMBLE_SECRET']
    end
    
More detailed usage example can be found [here](https://github.com/nimblecrm/ruby-example/tree/master/Sample%201).
