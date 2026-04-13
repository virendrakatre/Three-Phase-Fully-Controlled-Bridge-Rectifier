# 💫 About Me:
I am a 3rd-year B.Tech Electrical Engineering student at KDK College of Engineering, Nagpur. <br>My core interests lie at the intersection of Power Electronics,Industrial Automation (PLC/SCADA), and Data Science. <br>I am passionate about building efficient electrical systems and leveraging data-driven insights to solve complex engineering problems. <br>Currently, I am expanding my expertise through projects in VLSI design and participating in the Aspire Leaders Program (Cohort 1).


##  Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/[https://www.linkedin.com/in/virendrakatr](https://www.linkedin.com/in/virendrakatre ) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:virendra.s.katre@gmail.com) 

# Tech Stack:
![Matplotlib](https://img.shields.io/badge/MATLAB-%23ffffff.svg?style=plastic&logo=Matplotlib&logoColor=black)
# GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=virendrakatre&theme=default&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=virendrakatre&theme=default&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=virendrakatre&theme=default&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=virendrakatre&icon=0&color=0)](https://visitcount.itsvg.in)
## ⚡ Project Overview: 3-Phase Fully Controlled Rectifier
This repository contains a **MATLAB/Simulink** model of a 6-pulse thyristor bridge. It is designed to convert 3-phase AC into a controllable DC output by adjusting the firing angle ($\alpha$).
### ⚡ Circuit Diagram
![Circuit Diagram](Circuit%20Diagram.jpg)
## ▶️ How to Run the Simulation

1. Open **MATLAB R2021a or later**.
2. Navigate to the project directory.
3. Open the Simulink model file:
4. Set the firing angle **α** in the Pulse Generator blocks.
5. Click **Run** to observe input voltage, output voltage, and load current waveforms.
### 🔍 Key Features:
* **[ ](start_span)Circuit Topology:** 6-Thyristor bridge configuration for full-wave rectification[ ](end_span).
* **[ ](start_span)Control:** Uses six synchronized **Pulse Generators** for precise SCR triggering[ ](end_span).
* **[ ](start_span)Load:** Includes a **Series RL Load** to study inductive filtering and current behavior[ ](end_span).

### 📊Simulation Results & Analysis
The waveforms demonstrate the transition from AC to DC:
* **[ ](start_span)Input Voltage:** Shows the three-phase sinusoidal input with switching transients[ ](end_span).
* **[ ](start_span)Output Voltage (Yellow):** Shows the 6-pulse rectified DC waveform[ ](end_span).
* **[ ](start_span)Load Current (Purple):** Shows a smoothed DC current due to the inductive load[ ](end_span).
## 🔁 Comparative Study: Effect of Firing Angle (α)

| Firing Angle (α) | Average Output Voltage (Vdc) | Observation |
|------------------|-----------------------------|-------------|
| 30°              | High                         | Near-continuous conduction |
| 60°              | Medium                       | Increased ripple |
| 90°              | Low                          | Reduced DC output |

As the firing angle increases, the average DC output voltage decreases, validating the theoretical relationship between Vdc and α.
##  Key Observations

- Increasing firing angle **α** reduces the average DC output voltage.
- The RL load ensures smoother current due to inductive filtering.
- Output voltage ripple increases with higher firing angles.
- System demonstrates 6-pulse rectification characteristics.
###  Detailed Analysis
👉 [Download Full Waveform Result (PDF)](Waveform%20result.pdf)

### Mathematical Model
The average output voltage ($V_{dc}$) is calculated as:

$$
V_{dc} = \frac{3\sqrt{3}V_m}{\pi} \cos(\alpha)
$$
##  Future Scope

- Harmonic analysis and Total Harmonic Distortion (THD) evaluation.
- Closed-loop control using PI/PID controller.
- Hardware implementation using SCR triggering circuits.
- Comparison with uncontrolled and semi-controlled rectifiers.
---
📌 *This project demonstrates the practical application of power electronics principles through simulation-based analysis.*
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
