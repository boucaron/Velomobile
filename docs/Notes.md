# Velomobile Design Notes

## Overview
This document summarizes the iterative simulation results and design changes made on the velomobile project between 26/06/2025 and 30/06/2025.  
Simulations were performed at 17 m/s wind speed to evaluate drag, downforce, power, and drag coefficient (Cr).

---

### Velomobile 26/06/2025

Simulation 5/7 @ 17 m/s  
- Drag: 12.73 N  
- Downforce: 1.428 N  
- Flat: -0.320 N  
- Power: 12.734 W  
- Cr: 0.13295  

Notes:  
- Dimensions a bit unrealistic in height (too low)  
- Longer and larger otherwise than top level ones  
- Slight downforce, which is good

---

### Velomobile_01 (27/06/2025)

Increased height: 900 mm back, 700 mm front and reshaped

Simulation 5/7 @ 17 m/s  
- Drag: 16.4691 N  
- Downforce: 9.5845 N  
- Flat: -0.1139 N  
- Power: 279.975 W  
- Cr: 0.163071  

Notes:  
- Some downforce, can be better

---

### Velomobile_02 (27/06/2025)

Reshaped rear top to reduce recirculation

Simulation 5/7 @ 17 m/s  
- Drag: 15.8718 N  
- Downforce: 8.622 N  
- Flat: -0.5046 N  
- Power: 269.821 W  
- Cr: 0.157153  

Notes:  
- Small drag improvement

---

### Velomobile_03 (27/06/2025)

Streamlined front and rear further

Simulation 5/7 @ 17 m/s  
- Drag: 16.2928 N  
- Downforce: 8.352 N  
- Flat: -1.373 N  
- Power: 276.977 W  
- Cr: 0.161362  

Notes:  
- More drag, rear too thin causing drag increase

---

### Velomobile_04 (27/06/2025)

Reshaped front and sides, considering mirror integration or rear camera

Simulation 5/7 @ 17 m/s  
- Drag: 16.100 N  
- Downforce: 8.348 N  
- Flat: -0.8849 N  
- Power: 273.705 W  
- Cr: 0.159423  

Stopped at 92% convergence

---

### Velomobile_05 (27/06/2025)

Updated tail from case 02

Simulation 5/7 @ 17 m/s  
- Drag: 16.5913 N  
- Downforce: 7.76344 N  
- Flat: 0.234044 N  
- Power: 282.052 W  
- Cr: 0.164277  

Notes:  
- More drag, less downforce

---

### Velomobile_06 (27/06/2025)

Smoothed front, moved tail opening

Simulation 5/7 @ 17 m/s  
- Drag: 16.0533 N  
- Downforce: 9.433 N  
- Flat: -0.143037 N  
- Power: 272.906 W  
- Cr: 0.159274  

---

### Velomobile_07 (27/06/2025)

Reshaped tail slightly

Simulation 5/7 @ 17 m/s  
- Drag: 15.7555 N  
- Downforce: 9.37877 N  
- Flat: -0.374752 N  
- Power: 267.843 W  
- Cr: 0.156325  

Notes:  
- Tiny drag improvement, downforce similar

---

### Velomobile_08 (27/06/2025)

Rounded edges around shoulders

Simulation 5/7 @ 17 m/s  
- Drag: 13.4257 N  
- Downforce: 7.19616 N  
- Flat: -0.5625 N  
- Power: 228.337 W  
- Cr: 0.133111  

Notes:  
- ~15% drag reduction  
- Slightly less downforce and back recirculation

---

### Velomobile_09 (27/06/2025)

Added mini diffusers

Simulation 5/7 @ 17 m/s  
- Drag: 12.8289 N  
- Downforce: 9.93741 N  
- Flat: -0.477387 N  
- Power: 218.091 W  
- Cr: 0.128968  

Detailed simulation 6/7 @ 17 m/s:  
- Drag: 12.5543 N  
- Downforce: 8.90993 N  
- Flat: -0.792832 N  
- Power: 213.423 W  
- Cr: 0.126215  

---

### Velomobile_10 (27/06/2025)

Updated mini diffusers

Simulation 5/7 @ 17 m/s  
- Drag: 12.7168 N  
- Downforce: 10.1528 N  
- Flat: -0.486228 N  
- Power: 216.186 W  
- Cr: 0.129944  

Notes:  
- Slight improvement, no major change

---

### Velomobile_11 (28/06/2025)

Reshaped for 900 mm width

Simulation 5/7 @ 17 m/s  
- Drag: 11.636 N  
- Downforce: 4.21524 N  
- Flat: 0.348078 N  
- Power: 197.813 W  
- Cr: 0.127209  

Notes:  
- Nice improvement

---

### Velomobile_12 (28/06/2025)

Reshaped for 800 mm width

Simulation 5/7 @ 17 m/s  
- Drag: 9.68679 N  
- Downforce: -3.20247 N  
- Flat: -0.738912 N  
- Power: 164.675 W  
- Cr: 0.11455  

Detailed simulation 6/7 @ 17 m/s:  
- Drag: 8.44347 N  
- Downforce: -2.50214 N  
- Flat: 0.639693 N  
- Power: 143.539 W  
- Cr: 0.0998  

Notes:  
- Nice figures with slight lift (expected)

---

### Velomobile_13 (28/06/2025)

Added holes to release front high pressure to rear wake

Simulation 5/7 @ 17 m/s  
- Drag: 10.0007 N  
- Downforce: -0.156693 N  
- Flat: -0.708033 N  
- Power: 170.013 W  

Detailed simulation 6/7 @ 17 m/s:  
- Drag: 9.37283 N  
- Downforce: 2.56282 N  
- Flat: 0.263663 N  
- Power: 159.338 W  

Notes:  
- More downforce but slightly more drag  
- Need better hole placement

---

### Velomobile_14 (28/06/2025)

Moved holes slightly

Simulation 6/7 @ 17 m/s  
- Drag: 9.27698 N  
- Downforce: 3.07195 N  
- Flat: -0.398707 N  
- Power: 157.709 W  

Notes:  
- Good but not excellent

---

### Velomobile_15 (28/06/2025)

Removed holes, width to 700 mm, slightly larger tunnels

Simulation 6/7 @ 17 m/s  
- Drag: 7.93972 N  
- Downforce: 1.14831 N  
- Flat: 0.113155 N  
- Power: 134.975 W  
- Cr: 0.104685  

Notes:  
- Good but should be under 0.1 Cr for excellence

---

### Velomobile_16 (29/06/2025)

Reshaped behind the head

Simulation 6/7 @ 17 m/s  
- Drag: 8.176 N  
- Downforce: 2.936 N  
- Flat: 0.317966 N  
- Power: 138.992 W  
- Cr: 0.10785  

Notes:  
- More drag, not good enough

---

### Velomobile_17 (29/06/2025)

Reshaped rear differently

Simulation 6/7 @ 17 m/s  
- Drag: 8.5002 N  
- Downforce: 2.11017 N  
- Flat: -0.142272 N  
- Power: 144.503 W  
- Cr: 0.112144  

Notes:  
- Even more drag  
- Critical fillet too small, retrying

---

### Velomobile_18 (29/06/2025)

Updated critical fillet

Simulation 6/7 @ 17 m/s  
- Drag: 8.34623 N  
- Downforce: 1.75858 N  
- Flat: -0.25057 N  
- Power: 141.886 W  
- Cr: 0.110157  

Notes:  
- Slight improvement, still not enough

---

### Velomobile_19 (29/06/2025)

Back to case 15, increased fillet sizes

Simulation 6/7 @ 17 m/s  
- Drag: 7.77618 N  
- Downforce: 0.73067 N  
- Flat: -0.0758167 N  
- Power: 132.195 W  
- Cr: 0.102835  

Notes:  
- Better drag, new top so far after case 15

---

### Velomobile_20 (29/06/2025)

Back to case 15, reshaped side and added large fillets

Simulation 6/7 @ 17 m/s  
- Drag: 8.01533 N  
- Downforce: 3.5622 N  
- Flat: 0.028594 N  
- Power: 136.261 W  
- Cr: 0.108254  

Notes:  
- Not bad but more drag  
- More downforce but needs iteration

---

### Velomobile_22 (30/06/2025)

Back to case 15, using larger fillets than 19 case and added dual diffusers at 7° (tunnels still present)

Simulation 6/7 @ 17 m/s  
- Drag: 7.29248 N  
- Downforce: 5.09997 N  
- Flat: -0.516756 N  
- Power: 123.972 W  
- Cr: 0.0965123  

Notes:  
- Good new top performer
