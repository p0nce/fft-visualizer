# fft-visualizer

![Example screenshot](screenshot.jpg)

Plots magnitude and phase of STFT analysis interactively.
This is useful to visualize a FFT, including phase of each bin.

## How to run:

```
dub
```


## Usage:
```
fft-visualizer input.wav
```
Controls:
- RIGHT: move time forward
- LEFT: move time backward
- SHIFT + RIGHT: move time forward one sample 
- SHIFT + LEFT: move time backwar one sample
- CTRL + RIGHT: fast time forward
- CTRL + LEFT: fast time backward
- CTRL + SHIFT + RIGHT: move 25% of an analysis window forward
- CTRL + SHIFT + LEFT: move 25% of an analysis window backward
- UP/DOWN: rotate display phase
- P: compensate natural phase increase on/off
- W: rotate window choice


## What I'm seeing?

White line is the input signal, before window multiplying.
Red line is the magnitude spectrum, in dB.
The coloured stuff is the FFT bins, phase and magnitude in dB are plotted.
