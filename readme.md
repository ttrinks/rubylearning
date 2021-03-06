
# Rubylearning Project

This is a project that illustrates learning a programming language by writing unit tests.

The Idea is to create a file for each concept, e.g.

    classes.rb
    method_definitions.rb
    control_structures.rb
    loops.rb
    strings.rb
    arrays.rb
    hashes.rb
    symbols.rb
    iteration_idioms.rb # each, to
    enumerator.rb # esp. map & inject in http://ruby-doc.org/core-2.0.0/Enumerable.html
    regular_expressions.rb
    reading_and_writing_files.rb
    blocks_and_yield.rb # maybe just adapt https://github.com/neo/ruby_koans/blob/master/src/about_blocks.rb
    reflection.rb # get method names, find out if an object responds to a method, send a message to an object where you have the method name in a string

## Getting started

### Installing RSpec

First, you need to install rspec. You can either install it directly with

    gem install rspec

Or use [bundler](http://bundler.io/) to install it (which you will need for rails anyway)

    gem install bundler
    bundle

The latter installs all gems listed in `Gemfile` and creates Gemfile.lock stating the actual versions of the installed gems.


### Calling the Tests

You can either run all tests with

    rspec about/*.rb

or individual files with

    rspec <filename>
