# morbid-fortune

Tells fortunes based on DoT railroad casualties reports

## Usage

```
$ ./morbid-fortune
```

## Caveats

The data is quite messy (optional fields) so the output could just be wrong.
I am using a dumb heuristic to get things that look like long form text (any
field with more than eight characters)

## Prerequisites
Mac users need `gshuf` installed: `brew install coreutils`. 
