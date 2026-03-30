# FHSS-Simulator

I built this simulation to understand how radio communication holds up under interference.
It combines Binary Phase Shift Keying (BPSK) with Frequency-Hopping Spread Spectrum (FHSS), 
where the signal switches between different frequencies in a pseudorandom pattern.
This makes it harder for a single-frequency jammer to disrupt the entire message, since only some of the transmitted bits are affected

The script models a full transmit-channel–receive pipeline. 
It measures bit error rate (BER) and compares it to the expected BPSK performance, generates a spectrogram that shows the frequency hopping and interference,
also it exports a .wav file so you can hear what the signal sounds like

<img width="811" height="641" alt="Screenshot 2026-03-30 at 21 07 52" src="https://github.com/user-attachments/assets/0edfaa25-e507-4d5a-a21b-362b84cd1bc0" />

##  How to run it

1. Install the dependesis:
```bash
pip install numpy matplotlib scipy
```
2. Run the script:
```bash
python3 simulator.py
```
