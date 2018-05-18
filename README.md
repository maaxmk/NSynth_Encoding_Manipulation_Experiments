# NSynth Encoding Manipulation Experiments
By Max Keene

### Try it on <a href="https://colab.research.google.com/notebook#fileId=1bGUhlwP7UNJPc2ZpQsYGvvTK_Cm_H7Z8&scrollTo=0jGH2hExi_wh&sandboxMode=true">colab</a>

# Description
The goal of the experiments is to explore new musical possibilities with nsynth. The main focus around these experiments is on the modulation of an encoding in the lantent space that nsynth creates. When a sound is fed into the nsynth encdoer it is essentially given a point in that latent space, and by moving the point slightly the sound is changed slightly. The latent space of nsynth has 16 dimentions, which means there are 16 axes of control to potentially modulate. The axial position of an encoding is stored in what are called channels of the encoding. This is where it really gets musically interesting. The only known sonic effect of an individual channel is that the further its value is from zero the greater effect it has on what the decoder generates. Because of this it is very hard to exactly predict what sound the experiment will create, but it will be somewhat related to the originally encoded audio. My recommendation is to generate a lot of different manipulated encodings and decode them all at once, because you'll get some you like and some you don't.

# Examples
<a href="https://soundcloud.com/staaf_max_keene/swap/s-GYmFG?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Example 1</a>, <a href="https://soundcloud.com/staaf_max_keene/swap-guitar-epiano-0100000000000000/s-Sm7wP?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Example 2</a>, <a href="https://soundcloud.com/staaf_max_keene/swap-experiment-w-amen-beatbox/s-fATpC?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Example 3</a>, <a href="https://soundcloud.com/staaf_max_keene/swap-beat-box-2-mtume-juicy-fruit-0100000000000000/s-wTF6Z?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Example 4</a>, <a href="https://soundcloud.com/staaf_max_keene/swap-mtume-juicy-fruit-beat-box-2-0000000001000000/s-r6okG?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Example 5</a>, <a href="https://soundcloud.com/staaf_max_keene/gain-amen-0757-0737-0934-0981-0855-0804-0909-0890-0859-0900-0656-1064-1079-0958-1059-0699/s-DBbgu?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Example 6</a>

Source audio: <a href="https://soundcloud.com/staaf_max_keene/epiano/s-fHFFe?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Epaino</a>, <a href="https://soundcloud.com/staaf_max_keene/guitar/s-9jL67?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Guitar</a>, <a href="https://soundcloud.com/staaf_max_keene/amen/s-TEFl3?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Amen</a>, <a href="https://soundcloud.com/staaf_max_keene/beat-box-2/s-GGsmT?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Beatbox</a>, <a href="https://soundcloud.com/staaf_max_keene/mtume-juicy-fruit/s-wgbTf?in=staaf_max_keene/sets/nsynth-encoding-manipulation/s-dn6Nu">Mtume Juicy Fruit</a>


These examples were generated using various methods of manipulating NSynth encodings. They use the sound listed next to "Source audio"