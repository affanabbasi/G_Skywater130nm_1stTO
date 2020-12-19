# Analog & RF IPs 

## LVDS Receiver
Design of an LVDS receiver in Skywater 130nm. The receiver architecture consists of a biasing stage followed by two amplification stages—the simulated maximum frequency of 1.5Gs at 1.8V, TT corner & 25C.

Submodules:

Biasing Stage – AC coupled with common-mode biasing of 1.2V

CML Stage – Amplification stage with a gain of 5

Differential Stage – Gain of ~8

## Ring Oscillator
7 stage RO with enable

Designed with Skywater standard cells library. AND gate followed by 7 smallest inverters

## Differential VCO
5 stages of differential delay cells. Delay cell consists of symmetric loads

Submodule:

Self bias generator with startup circuit

## Power Amplifier
Linear Class AB power amplifier. On-chip inductor is designed as a test structure by using top metal layer. Actual inductance & Q factor is unknown

## Folded Cascode
Differential input single ended Folded Cascode Opamp; 1Mhz unity gain frequency, 60 degree phase margin & a gain of 79dB
