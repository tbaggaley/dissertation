# Extempore & MIDI control

## Using the files with Extempore

Extempore tries to find files loaded using `(sys:load filename)` by looking in the Extempore working directory. The files included here must be placed in a "tom" subdirectory within the main extempore directory in order for their include statements to function as-is.

## Typical use

A typical demonstration application would include `rtmidi-stream.xtm` and the Extempore standard "shared system" to achieve behaviours such as arpeggiation. Adding in `recording.xtm` allows access to the recording, looping and sequencing abstractions. Some examples of behaviour are available in `demo.xtm`, which served as a scratchpad for testing code throughout the project lifecycle. 

Thomas Baggaley
Sep 2020
