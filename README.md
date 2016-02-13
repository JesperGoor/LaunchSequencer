# LaunchSequencer

I have long wanted to turn my combination of a Novation LaunchPad and a LaunchControl into sequencer.

I have attempted this several times using Native Instruments Reaktor. These attempts inevitably resulted in me once again realizing 
just how much Reaktor needs some sort of clone feature, where cloned instances track changes in the original. Plus, the event processing
required to do these sort of things in Reaktor always leaves me longing for regular code.

Thus, I have decided to attempt to combine Reaktor and a custom VST plugin instead. Reaktor will handle the audio processing, while the
(pure MIDI) VST pluging will handle the sequencing, as well as the interface with the Novation controllers.

This repository represents the VST part. I originally wanted to develop it in C++, but since I needed to brush up on my Java skills anyway,
I decided to use Java. Performance is not critical anyway, as the audio processing will all be done in Reaktor.

## Installation

Not yet applicable.

## Usage

Not yet applicable.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

2016 Feb 13: First commit. Still in planning process.

## Credits

All code written by Jesper Goor Pedersen.

## License

Not yet applicable.
