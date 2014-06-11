## SublimeRubyHashRocket

Simple plugin for input Ruby hash rocket ( => ) by a shortcut.

## Installation

### Clone from GitHub
Alternatively, you can clone the repository directly from GitHub into your Packages directory:

    git clone git@github.com:dddaisuke/SublimeRubyHashRocket.git
    
        or
    
    git clone https://github.com/dddaisuke/SublimeRubyHashRocket

## Key binding

    {
      "keys": ["super+l"],
      "command": "run_macro_file",
      "args": { "file": "Packages/SublimeRubyHashRocket/HashRocket.sublime-macro" },
      "context": {
        "key": "selector", "operator": "equal", "operand": "source.ruby"
      }
    }

## Credits

- dddaisuke <http://twitter.com/dddaisuke>

## License

All of SublimeRubyHashRocket is licensed under the MIT licence.
