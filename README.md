# 5.1-channel-preamplifier-for-Audio-system
This one supports 4 channels for different speakers at 25watts each plus a 100watt subwoofer channel which makes it the best of its own.
Get more info from here: https://www.instructables.com/51-Channel-Preamplifier-for-Audio-System/
GO to JLCPCB: https://jlcpcb.com/SSR
Watch video from here: https://youtu.be/gHqiPI_tWK4

I want to make a big party boom box, with a 100watt subwoofer and four speakers of 25 watts each. But we need a better amplifier and preamplifier board which can meet the requirements. I searched a lot but some of the amplifier systems are very expensive or some of them even do not support 5 channel surround sound output.
That’s why I ought to design my own preamplifier and amplifier board. So, we need a maximum output of 200watts but before that a better surround sound preamplifier board is needed. This article is sponsored by JLCPCB and if you sign-up to JLCPCB you will get a new user coupon of $54 to place the prototypes order.

Basic Idea of working and components selection:
Because we are dealing with frequencies between 0-14khz (suitable audio range). Which can be further divided into 3 categories- bass, mid and treble. For lower range frequency (for bass) we need a high slew rate and low noise ic that’s why for this we can use JRC4558D. It will fulfil the requirements of 100watts subwoofer. For speakers we can use lm324 four operational amplifier ic which can be used as a buffer in 2x gain multiplier for the all four speakers.

Components list:
1. JRC4558D dual operational amplifier
2. LM324 Quad channel op-amp
3. 100K, 47K preset (for bass and volume control)
4. Resistors: 1k, 3.3k, 4.7k, 6.8k, 8.2k, 10k, 22k, 27k, 47k, 100k, 150k
5. Polyester film Capacitors: 100nf and 1nf
6. Electrolytic capacitors: 1uf, 4.7uf, 47uf, 1000uf
7. In4007 diodes
8. Bluetooth chip
9. AMS1117 5v (voltage regulator)

PCB designing:
I designed the schematics in EasyEDA and manufactured it from JLCPCB in just $2. JLCPCB is providing the PCB prototypes in the lowest price and the quality is always amazing. You can see those glossy finish on the PCBs. You can check the latest news updated on the webpage of JLC and they are making the projects more practical with dual side real PCBA assembly service.  https://drive.google.com/drive/folders/1Q_1VPaH49UK6lDqRijeZ88Oufsvt5hIb?usp=sharing
If you want to use the same designs as mine then Download them from here. And if you sign-up to JLCPCB using this link you will get $54 new user coupon as a welcome reward which can be used to order the PCBs, PCBA, stencil and 3D printed parts accordingly.

PCB specs:
Our PCB has Onboard power supply, 4 channel speaker audio outputs and 1 subwoofer output, 5volt supply for the small Bluetooth system, Subwoofer and volume control presets, Desirable gain output for the speakers.

Working and observations:
High frequency has a little more gain over bass, so the lm324 can be modified to give lower gain by changing this resistor here. If you want to know more about OP-amp workings as buffer then read this article. The bass gives a very high punch which can easily drive a subwoofer of 12inches. The sound is very loud while I am testing this with TDA7294 subwoofer amplifier and TDA7265 speaker amplifier. Both of the amplifier is classified in class AB and known for their high-performance high-fidelity output.

Amplifier making:
Now out preamp is ready for the party boom box, it is the turn for the amplifier and I will go with TDA series IC amplifier due to their output and efficiency. We will build amplifier circuit using JLCPCBs PCB prototyping service to get the proper output from this preamplifier system. Till then stay tuned and don’t forget to have a look on the exciting offers from JLCPCB. 
GO to JLCPCB: https://jlcpcb.com/SSR
