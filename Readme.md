# Cellular Network Analysis - Wireless and Radiotechnology 2026

## Objective
To analyze cellular network parameters (LTE/5G) using iPhone Field Test Mode to understand how environment affects connectivity.

## Experiment Setup
- **Device:** iPhone
- **Tool:** Field Test Mode (*3001#12345#*)
- **Operator:** DNA (Finland)

## Collected Data
| Location | Tech | Band | RSRP | RSRQ | SINR |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Indoors (Current) | LTE | 3 | -89 dBm | -11 dB | 7.8 dB |
| Outdoors | LTE | 3 | [Enter Value] | [Enter Value] | [Enter Value] |

## Technical Analysis
### 1. Signal Strength (RSRP)
The measured RSRP of -89 dBm indicates a reliable connection. However, as I move deeper into the building, physical obstructions like concrete walls cause 'Path Loss,' potentially dropping this value toward -110 dBm.

### 2. Signal Quality (SINR & RSRQ)
With a SINR of 7.8 dB, there is noticeable background noise. This suggests high network load or interference from electronic devices. Lower SINR directly reduces the MCS (Modulation and Coding Scheme), leading to slower data speeds.

### 3. Bandwidth
The 20 MHz bandwidth on Band 3 (1800 MHz) provides a high capacity for data throughput, assuming the SINR remains stable.

## Conclusions
The environment significantly impacts the Signal-to-Noise ratio. Even with decent power (RSRP), poor quality (SINR) can lead to packet loss and reduced network stability.
