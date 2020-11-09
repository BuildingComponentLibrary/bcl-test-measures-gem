# BCL Test Measures Gem

This measure repo is used to test the new BCL codebase and to demonstrate the appropriate structure of measure repos to be added to the BCL.  Measures should be placed in the `lib` directory.

Measure repositories should be structured as an [OpenStudio extension gem](https://github.com/NREL/openstudio-extension-gem).  Follow the directions to [initialize a new extension gem](https://github.com/NREL/openstudio-extension-gem#initializing-a-new-extension-gem) for your measures and use the rake task to test your measures.  

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'bcl-test-measures'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install 'bcl-test-measures'

## Usage

This is used for testing purposes only

# Releasing

* Update change log
* Update version in `/lib/openstudio/bcl-test-measures/version.rb`
* Merge down to master
* Release via github
* run `rake release` from master
