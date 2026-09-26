# PHASE-MODULATION-USING-SCILAB---T1---M4---ODD


## Aim
To implement and analyze Phase Modulation (PM) using Scilab.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike Frequency Modulation (FM), where the frequency is varied, in Phase Modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.

### Mathematical Representation
The general form of a Phase Modulated signal $s(t)$ is given by:

$$s(t) = A_c \cos(2\pi f_c t + k_p m(t))$$

Where:
* $A_c$ : Amplitude of the carrier wave
* $f_c$ : Carrier frequency
* $m(t)$ : Message signal, typically $m(t) = A_m \cos(2\pi f_m t)$
* $k_p$ : Phase deviation sensitivity (in radians/volt)

---

## Algorithm
1. **Initialize Parameters:**
   * Define carrier amplitude ($A_c$), carrier frequency ($f_c$), message frequency ($f_m$), sampling frequency ($f_s$), and phase sensitivity ($k_p$).
2. **Generate Time Axis:**
   * Create a time array $t$ with suitable sampling steps over the signal duration.
3. **Generate Message Signal:**
   * Compute the message signal vector $m(t)$ using the cosine function.
4. **Generate Carrier Signal:**
   * Compute the unmodulated carrier signal vector $c(t) = A_c \cos(2\pi f_c t)$.
5. **Generate PM Signal:**
   * Compute the phase-modulated signal $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$.
6. **Plot the Signals:**
   * Use Scilab's plotting commands (`subplot`, `plot`, `xtitle`, `xgrid`) to display message, carrier, and modulated signals.

---
## CALCULATION
<img width="1280" height="960" alt="WhatsApp Image 2026-09-26 at 10 08 15 AM" src="https://github.com/user-attachments/assets/7b4f44bf-65e9-489e-b2e6-b9c4a33dc451" />


## OUTPUT
<img width="1483" height="896" alt="WhatsApp Image 2026-09-23 at 12 48 11 PM" src="https://github.com/user-attachments/assets/29789cc4-c6ba-4273-84e5-dbed2df1815a" />
## TABULATION
<img width="1280" height="866" alt="WhatsApp Image 2026-09-26 at 9 52 20 AM" src="https://github.com/user-attachments/assets/0781c658-66ae-4cd9-b480-67ea282b7433" />

Result
<img width="1280" height="497" alt="WhatsApp Image 2026-09-26 at 11 58 17 AM" src="https://github.com/user-attachments/assets/7d530083-cc78-4abd-947a-5b06ec41cc3c" />

The message signal, carrier signal, and phase-modulated (PM) signal will be displayed in separate plots. The modulated signal will show phase variations corresponding to the amplitude of the message signal.
