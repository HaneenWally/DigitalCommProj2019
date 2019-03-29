# DigitalCommProj2019
A project to simulate the performance of different modulation schemes, BPSK, QPSK, FSK, QAM(16-64) in an AWGN environment.

# Contents of README
* BPSK
  1. Explanation.
  2. Instructons to produce figures.
  3. Scatter plots
    - At transmitter.
    - At receiver.
  4. BER performance figure.
  
* QPSK
  1. Explanation.
  2. Instructons to produce figures.
  3. Scatter plots
    - At transmitter.
    - At receiver.
  4. BER performance figure.
  
* FSK
  1. Explanation.
  2. Instructons to produce figures.
  3. Scatter plots
    - At transmitter.
    - At receiver.
  4. BER performance figure.
  
* QAM16
  1. Explanation.
  2. Instructons to produce figures.
  3. Scatter plots
    - At transmitter.
    - At receiver.
  4. BER performance figure.

* QAM64
  1. Explanation.
  2. Instructons to produce figures.
  3. Scatter plots
    - At transmitter.
    - At receiver.
  4. BER performance figure.
  5. Instructions to change 64 points
  6.  Scatter plots
    - At transmitter.
    - At receiver.
  7. BER performance figure.

# BPSK Explanation
Binary Phase Shift Keying is a form of phase shift keying and is acheived by simply changing the phase of the carrier corresponding to the value of the modulating signal, for example if sent symbol is 1 carrier signal = A cos(2 pi _f_ t) and when it's 0 carrier = A cos(2 pi _f_ t + theta), where theta is the phase change and since it's binary, the phase change value is 180 degrees (pi).

# Instructions
After running MATLAB in command prompt type "EbNo = 0;", press enter, 
then type "bertool", press enter as shown here
![command prompt image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.35.53%20AM.png)

set parameters in theoritical tab as shown 
![bpsk theotab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.31.02%20AM.png)

press plot,
then in monte carlo tab set all parameters as shown except in Simulation MATLAB file or Simulink model choose file/model on your PC from browse option or copy and paste path
![bpsk montcartab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.30.58%20AM.png)

press run.
you should see similar plots as provided here

# Scatter Plots
* At Transmitter
![bpsk beforeN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%2011.15.17%20AM.png)

* At Receiver
![bpsk AfterN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%2011.15.20%20AM.png)

# BER Performance Figure
![bpsk berplot image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%2011.15.14%20AM.png)

# QPSK Explanation

Quadrature Phase Shift Keying is also a form of phase shift keying, but it's more efficient as it uses same bandwidth as BPSK, but sends two symbols instead of one at a time, example 00 at 0 degree, 01 at 45 degrees, 10 at 90 degrees and 11 at 135 degrees.

# Instructions
After running MATLAB in command prompt type "EbNo = 0;", press enter, 
then type "bertool", press enter as shown here
![command prompt image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.35.53%20AM.png)

set parameters in theoritical tab as shown 
![qpsk theotab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.42.04%20AM.png)

press plot,
then in monte carlo tab set all parameters as shown except in Simulation MATLAB file or Simulink model choose file/model on your PC from browse option or copy and paste path
![qpsk montcartab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.42.01%20AM.png)

press run.
you should see similar plots as provided here

# Scatter Plots
* At Transmitter
![qpsk beforeN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.41.52%20AM.png)

* At Receiver
![qpsk AfterN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.41.58%20AM.png)

# BER Performance Figure
![qpsk berplot image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.41.54%20AM.png)

# FSK Explanation

Frequency Shift Keying is a modulation scheme where the sent symbol changes the frequency of the carrier signal, for example when sending 0 frequency of carrier = _f1_, and when sending 1 frequency of carrier = 2 times _f1_, here we're using 8 different frequencies ie 3 symbols are sent at a time.

# Instructions
After running MATLAB in command prompt type "EbNo = 0;", press enter, 
then type "bertool", press enter as shown here
![command prompt image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.35.53%20AM.png)

set parameters in theoritical tab as shown 
![fsk theotab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.38.50%20AM.png)

press plot,
then in monte carlo tab set all parameters as shown except in Simulation MATLAB file or Simulink model choose file/model on your PC from browse option or copy and paste path
![fsk montcartab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.38.45%20AM.png)

press run.
you should see similar plots as provided here

# Scatter Plots
* At Transmitter
![fsk beforeN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.38.26%20AM.png)

* At Receiver
![fsk afterN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.38.35%20AM.png)

# BER Performance Figure
![fsk berplot image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.38.18%20AM.png)

# QAM16 Explanation

Quadrature Amplitude Modulation is a modulation scheme where two carriers are sent together with phase shift of 90 degrees instead of one carrier and each carrier represents a symbol defined by its amplitude, using same concept, but with more phase differences and multiple amplitude levels we can acheive qam8, qam16, qam32, ..etc

# Instructions
After running MATLAB in command prompt type "EbNo = 0;", press enter, 
then type "bertool", press enter as shown here
![command prompt image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.35.53%20AM.png)

set parameters in theoritical tab as shown 
![qam16 theotab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.44.37%20AM.png)

press plot,
then in monte carlo tab set all parameters as shown except in Simulation MATLAB file or Simulink model choose file/model on your PC from browse option or copy and paste path
![qam16 montcartab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.44.35%20AM.png)

press run.
you should see similar plots as provided here

# Scatter Plots
* At Transmitter
![qam16 beforeN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.44.26%20AM.png)

* At Receiver
![qam16 AfterN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.44.32%20AM.png)

# BER Performance Figure
![bpsk berplot image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.44.28%20AM.png)

# QAM64 Explanation

same as QAM16, but adding more phases and amplitude levels.

# Instructions
After running MATLAB in command prompt type "EbNo = 0;", press enter, 
then type "bertool", press enter as shown here
![command prompt image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.35.53%20AM.png)

set parameters in theoritical tab as shown 
![qam64 theotab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.47.20%20AM.png)

press plot,
then in monte carlo tab set all parameters as shown except in Simulation MATLAB file or Simulink model choose file/model on your PC from browse option or copy and paste path
![qam64 montcartab image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.47.17%20AM.png)

press run.
you should see similar plots as provided here

# Scatter Plots
* At Transmitter
![qam64 beforeN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.47.10%20AM.png)

* At Receiver
![qam64 AfterN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.47.15%20AM.png)

# BER Performance Figure
![qam64 berplot image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.47.11%20AM.png)

_*The 64 point are distributed according to average power, you can choose them according to minimum distance by doing the following*_

open the qam64.slx model

double click on qam64 modulator block 
![qam64 mindis mod image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%2011.11.54%20AM.png)

do the same for qam64 demodulator block 
![qam64 mindis dem image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%2011.12.32%20AM.png)

and follow same steps as above to produce figures

# Scatter Plots
* At Transmitter
![qam64 beforeN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.49.45%20AM.png)

* At Receiver
![qam64 AfterN image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.49.46%20AM.png)

# BER Performance Figure
![qam64 berplot image](https://github.com/HaneenWally/DigitalCommProj2019/blob/master/imgs/Screen%20Shot%202019-03-29%20at%209.49.49%20AM.png)
