## The 3722a noise generator

Repository for research and development with the Hewlett-Packard 3722A Noise Generator with Option 01.

![image](/images/3722a-front.jpg)

The Model 3722A Noise Generator uses digital techniques to synthesize binary and Gaussian noise patterns. These _pseudorandom_ patterns, which are of known content and duration, are repeated over and over without interruption. Since one pattern is identical with th4 net, each pattern has the same effect on the system under test: For this reason, pseudorandom noise signals cause no statistical variance in test results. The Model 3722A also generates truly random binary and Gaussian noise.

### table of contents

* What is the art of precision [noise](/art-of-noise/README.md)?

### Instrument details

The basis of the Model 3722A is a binary waveform generator--a shift register which operates under the control of either a feedback mechanism (pseudorandom mode) or a random noise source (random mode). The shift register is clock triggered, with the result that transitions between output levels of the binary waveform can occur only in time with beats of the clock--although whether or not a transition occurs on a given beat is determined by the feedback mechanism or random noise source. The binary output has a $`sin x/x^2`$-shaped spectrum and the Gaussian output, which is derived from the binary signal by precision low-pass filtering, has an almost rectangular spectrum. Both binary and Gaussian outputs are controllable in bandwidth, but the output power remains constant regardless of selected bandwidth--a particularly useful feature, of importance in applications where usable noise power must be made available in a very restricted frequency band. Frequency of the first null in the binary spectrum is selectable from 0.003 Hz to 1 MHz, and the bandwidth, at the -3 dB point, of the Gaussian noise is selectable from 0.00015 Hz to 50 kHz.

Outputs from the Model 3722A are available at fixed amplitudes of +/- 10 V (binary) and 3.16 V rms (Gaussian), and a precision amplitude control provides a variable output of either signal ranging from 0.1 V rms up to the level of the fixed outputs.
