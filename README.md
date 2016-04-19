# GraphvizAasm

Adds support for generating graphs based on states, events and transitions defined for [Transitions](https://github.com/troessner/transitions) state machine using
[GraphViz](http://www.graphviz.org) and [Ruby-GraphViz](https://github.com/glejeune/Ruby-Graphviz).
It is a simplified version of the same functionality for [state_machine](https://github.com/pluginaweek/state_machine) gem.

## Installation

Add this line to your application's Gemfile:

    gem 'graphviz_transitions', group: :development

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install graphviz_transitions

## Usage

To generate a graph for a specific model:

    $ rake transitions:draw CLASS=Vehicle

To save files to a specific path:

    $ rake aasm:draw CLASS=Vehicle,Vehicle::Color TARGET=./tmp


## Contributing

1. Fork it ( http://github.com/itkin/graphviz_transitions/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## Credit 

[romatr/graphviz_aasm](https://github.com/romatr/graphviz_aasm)