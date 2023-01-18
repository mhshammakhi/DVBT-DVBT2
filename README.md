# DVBT-DVBT2

## DVBT

In This project I present the cpu based DVBT protocol as a transmitter and I am developing GPU based receiver.
 
 The main featurs of the implimeted code are:
  - It contains Qt based GUI
  - It is cross-platform
  - You can transmit each ts file by using this project


In This project, the transmitter is based on a MATLAB code one of my friends released. You can find it [in his github page](https://github.com/mkh1992/DVBT-Transmitter).

For the transmitter we should implement these processing blocks[^1]:
- [x] PRBS Sequence Generator
- [x] Reed Solomon Encoder
- [x] Data Interleaver
- [x] Convolutional Encoder
- [ ] Data Demultiplexer






## References:

[^1]: [protocol and Standard details](https://www.etsi.org/deliver/etsi_en/300700_300799/300744/01.06.01_60/en_300744v010601p.pdf)
