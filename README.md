# A Compact High-Gain Dual-Circularly Polarized Antenna Based on High-Order Mode Microstrip Patch

This repository contains the simulation models for the antenna presented in our paper submitted to **IEEE Latin America Transactions**. The design utilizes high-order mode excitation combined with slot-loading techniques to achieve high gain within a compact footprint.

## 1. Overview
This research introduces a high-gain dual-circularly polarized (CP) antenna that avoids the complexity and size of traditional array or Fabry-Perot structures. The design is based on the following principles:
* **High-Order Mode Excitation:** A square patch is excited to operate in the high-order $TM_{03}$ mode to enlarge the effective radiating aperture and enhance gain.
* **Grating Lobe Suppression:** Four open slots are etched on the patch edges to suppress grating lobes and reduce the overall physical size.
* **Dual-CP Operation:** A $90^{\circ}$ hybrid coupler serves as the feeding network to produce either right-hand CP (RHCP) or left-hand CP (LHCP) with high isolation.

## 2. Design Specifications
The antenna is modeled on a high-frequency substrate with the following characteristics:
* **Substrate:** Taconic TLY-5
* **Dielectric Constant ($\epsilon_r$):** $2.2$
* **Loss Tangent ($\tan \delta$):** $0.0009$
* **Thickness ($h$):** $1.52$ mm
* **Center Frequency ($f_c$):** $5.6$ GHz (compatible with IEEE 802.11a/ac systems)
* **Overall Dimensions:** $1.49\lambda \times 1.49\lambda \times 0.04\lambda$

## 3. Performance Summary
Measured results from the fabricated prototype demonstrate:
* **Peak Realized Gain:** Approximately $12.0$ dBi
* **Axial Ratio (AR):** Below $3$ dB across the $5.55$–$5.7$ GHz band
* **Return Loss ($|S_{11}|$):** Better than $20$ dB at the center frequency
* **Port Isolation ($|S_{21}|$):** Approximately $22$ dB
* **Front-to-Back Ratio:** Approximately $18$ dB

## 4. Repository Structure
* `/HFSS_Models`: Contains the `.aedt` files for the patch antenna and the branch-line hybrid coupler.

## 5. Applications
The proposed antenna is suitable for applications where long-range performance and orientation robustness are critical:
* UAV communications
* Point-to-point back-haul
* Satellite and IoT systems

## 6. License
