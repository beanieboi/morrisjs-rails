# morrisjs-rails

morris.js for the Rails Asset Pipeline

## Dependency on jQuery

This library requires jQuery. If you are using Rails 5.1 or later, jQuery is not included in a new installation. You need to add jQuery to Rails by yourself.

## Installation

Add this to your application's Gemfile:

    gem 'morrisjs-rails'
    gem 'raphael-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install morrisjs-rails
    $ gem install raphael-rails

## Usage

Add the following directive to your Javascript manifest file (application.js):

    //= require raphael
    //= require morris
    
Add the following directive to your css manifest file (application.css):

     *= require morris


Add the following directive to your sass manifest file (application.scss):

     @import 'morrisjs-rails';


## Versioning

The naming schema is identical to morris.js.


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
