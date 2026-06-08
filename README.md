# Chorus Pedal
Analog electric guitar chorus pedal that utilizes a PT2399 echo audio processor IC. It features a LFO with a sine/triangle wave toggle and speed and depth controls, as well as a dry signal bypass switch.

The chorus effect, as the name suggests, aims to emulate a "choir" sound. This is achieved through modulating delay, as applying a constant delay to a signal does not alter the frequency of the signal. A time-varying delay will actually shift events of the wave (crests and troughs, for instance), which changes the period of the wave. Since frequency is the inverse of the period, a decreasing or increasing delay will cause an increase or decrease in frequency respectively. The minor frequency shifted signals act as distinct voices, eventually getting mixed in with the original signal to form the chorus sound.

## Delay

## LFO
So how does one achieve a modulating delay? 
