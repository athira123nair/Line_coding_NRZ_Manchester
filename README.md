# Line_coding_NRZ_Manchester
Non-return-to-zero [NRZ] – 
NRZ code’s voltage level is constant during a bit interval. When there is a long sequence of 0s and 1s, there is a problem at the receiving end. The problem is that the synchronization is lost due to a lack of transmissions. 
It is of 2 types: 

NRZ-level encoding – 
The polarity of signals changes when the incoming signal changes from ‘1’ to ‘0’ or from ‘0’ to ‘1’. It considers the first bit of data as polarity change.
NRZ-Inverted/ Differential encoding – 
In this, the transitions at the beginning of the bit interval are equal to 1 and if there is no transition at the beginning of the bit interval is equal to 0.
Characteristics of Manchester Encoding –

A logic 0 is indicated by a 0 to 1 transition at the center of the bit and logic 1 by 1 to 0 transition.
The signal transitions do not always occur at the ‘bit boundary’ but there is always a transition at the center of each bit.
The Differential Physical Layer Transmission does not employ an inverting line driver to convert the binary digits into an electrical signal. And therefore the signal on the wire is not opposite the output by the encoder.
The Manchester Encoding is also called Biphase code as each bit is encoded by a positive 90 degrees phase transition or by negative 90 degrees phase transition.
The Digital Phase Locked Loop (DPLL) extracts the clock signal and deallocates the value and timing of each bit. The transmitted bitstream must contain a high density of bit transitions.
The Manchester Encoding consumes twice the bandwidth of the original signal.
The advantage of the Manchester code is that the DC component of the signal carries no information. This makes it possible that standards that usually do not carry power can transmit this information.
 
