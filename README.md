# 🌌 Real-World Applications of TM and TE Waves Between Parallel Plates used in VOYAGER 1 #

About **voyager 1**

Voyager 1 has been exploring our solar system since 1977. The probe is now in interstellar space, the region outside the heliopause, or the bubble of energetic particles and magnetic fields from the Sun. Voyager 1 was launched after Voyager 2, but because of a faster route it exited the asteroid belt earlier than its twin, and it overtook Voyager 2 on Dec. 15, 1977.

Voyager 1 discovered a thin ring around Jupiter and two new Jovian moons: Thebe and Metis.

At Saturn, Voyager 1 found five new moons and a new ring called the G-ring.

Voyager 1 was the first spacecraft to cross the heliosphere, the boundary where the influences from outside our solar system are stronger than those from our Sun.

Voyager 1 is the first human-made object to venture into interstellar space.

![1-Voyager_2-copy](https://github.com/user-attachments/assets/9f978770-6a2c-48a5-ad21-7a0eca9d4bc1)

1. Microwave Waveguides in Radar & Communication Systems

**📡 Application:**

Parallel plate waveguides that support TE and TM modes are used in radar systems and satellite communication to guide microwaves efficiently with minimal loss.

**🛠️ How It Works:**

TE and TM modes define how the electric (E) and magnetic (H) fields are distributed between the plates.

These waveguides carry signals in systems like space-borne radar antennas, including those on deep space probes like Voyager 1.



🛰️ MODULE A – FUNDAMENTAL EQUATIONS SCANNED

Subject: Two infinite parallel conducting plates separated by a distance d, wave propagating in the z direction.

## **📘 TE (Transverse Electric) Waves** ##

 ![image](https://github.com/user-attachments/assets/218d6e03-1b3d-4cba-a5d2-27e266984fdc)

Dominant mode: TE₁

Cutoff frequency:

![image](https://github.com/user-attachments/assets/3cdac6fa-d5de-49ac-9430-c203fe17d9cd)

Electric field between plates:

![image](https://github.com/user-attachments/assets/f3576c77-81b4-4ee7-803c-eff008663b39)

 
## **📘 TM (Transverse Magnetic) Waves** ##

![image](https://github.com/user-attachments/assets/bef85377-4c5f-4781-a7e6-26aac738803d)

Dominant mode: TM₁

Cutoff frequency:
![image](https://github.com/user-attachments/assets/e9115de0-f660-49fc-8730-b1161f849677)

Magnetic field:

![image](https://github.com/user-attachments/assets/ce341b3d-f283-4af7-b28b-c046a95d8839)

TM and TE waves between parallel plates

![image](https://github.com/user-attachments/assets/0746e359-9ce1-4df6-9f6c-e60eb3cf0b25)





## 🌍 VOYAGER-EM APPLICATION MODULES ##


### **🛰️ MODULE B1: Microwave Heating (TM₁ Mode)** ###

Location: Domestic Food Processing Chamber

Observed EM Field: TM₁₀ dominant in parallel metal walls of microwave oven.

🧪 Scientific Explanation:

TM₁ waves generate strong longitudinal E-fields → couples energy to dielectric (water in food).

Efficient for uniform volumetric heating.

🔬 Application Snapshot:

Frequency: 2.45 GHz (Industrial microwave standard)

Plate separation d ≈ 6.1 cm (resonant cavity tuned to TM₁₀)

Enhanced E-fields excite dipolar molecules → vibration → heat


### **🛰️ MODULE B2: Rectangular Waveguide Communications (TE₁₀ Mode)** ###

Location: Ground Radar Transmitter Array

🧪 Scientific Explanation:

TE₁₀ wave (dominant mode) in rectangular waveguide acts like parallel plate with boundary in one direction.

E-field transverse to direction of propagation.

🔬 Application Snapshot:

Used in X-band radar (8–12 GHz)

Plate height d set so:

![image](https://github.com/user-attachments/assets/d34b0b00-329c-4fd4-8bd5-5622dd733cb7)

 
No E_z → stable, low-loss transmission over long paths

📡 Key Use Case:

Weather radar, aircraft surveillance, early warning systems


### **🛰️ MODULE B3: Stripline PCBs (Quasi-TEM)** ###

Location: 5G Base Station Hardware Node

🧪 Scientific Explanation:

Signals between flat metal strips inside PCB layers are combinations of TE and TM → quasi-TEM.

Controlled by permittivity and geometry of PCB dielectric.

🔬 Application Snapshot:

Impedance:

![image](https://github.com/user-attachments/assets/2030cafd-7d16-4556-8327-5a9d3c4010c7)

Where h is height to ground plane and w is conductor width.

📡 Key Use Case:

High-frequency PCB design (mmWave)

Used in smartphones, satellites, and defense RF modules


### **🛰️ MODULE B4: Optical Dielectric Slab Waveguides (TE & TM)** ###

Location: Silicon Photonics Research Deck

🧪 Scientific Explanation:

Light confined between high-index slab supports TE and TM modes.

Different propagation constants for each due to boundary conditions.

🔬 Application Snapshot:

Effective Index:

![image](https://github.com/user-attachments/assets/2e28e0b5-7903-456a-a69a-f168aab331b9)

 
Optical sensors use TM-mode's surface sensitivity for biosensing.

📡 Key Use Case:

On-chip optical routing, lab-on-chip biosensors, photonic computing


### **🛰️ MODULE B5: Plasma Heating (High-Power TE & TM Injection)** ###

Location: International Fusion Reactor Core (ITER Prototype)

🧪 Scientific Explanation:

Waveguides inject high-frequency TE or TM waves to couple RF power into plasma.

E-field aligns with particle motion → efficient cyclotron resonance heating

🔬 Application Snapshot:

TM waves → strong longitudinal fields for electron acceleration

TE modes → stability for ion heating


## **⚛️ Application:** ##

TM modes are used in accelerating cavities where electric fields aligned along the beam axis accelerate particles.This is essential for large-scale accelerators like CERN’s LHC and SLAC.


🔍 TM Mode Role:

TM₀₁ mode provides a longitudinal electric field ideal for accelerating charged particles.

Parallel plate approximations are used in early-stage design before transitioning to more complex cavity shapes.

Metamaterials and Cloaking Devices


 **Deep Space Probes – Voyager 1 Communications**

🚀 Application:

Though Voyager 1 doesn’t carry open parallel plate waveguides, its high-gain antenna and transmitter waveguides use rectangular or ridged waveguides—which are modeled as combinations of TE/TM between parallel plates.

**Role of TE/TM modes:**

TE₁₀ mode is dominant in Voyager’s X-band waveguide (~8.4 GHz uplink, ~7.2 GHz downlink).

It ensures efficient transmission of weak signals over 22 billion kilometers.

📡 Antennas Based on TE Modes:

The propagation characteristics of TE waves determine how the electromagnetic field behaves within the feed system of the Voyager antenna.

The design is modeled after parallel plate systems to simplify and optimize EM simulations.

📷 nasa jet propulsion lab & voyager antenna schematics:

![images](https://github.com/user-attachments/assets/020b8710-5224-48dd-aa12-8d67123cbf49)


## **MODE USED IN VOYAGER 1** ##

| Application                      | Mode Used | Real-World Example                                | Frequency Band     |
| -------------------------------- | --------- | ------------------------------------------------- | ------------------ |
| Spacecraft Waveguides            | TE₁₀      | Voyager 1 communication waveguides                | 7–8.4 GHz (X-band) |
| Particle Accelerators            | TM₀₁      | SLAC, LHC                                         | GHz-range          |
| Radar & Antenna Feed Lines       | TE        | Ground radar, spacecraft antennas                 | 1–40 GHz           |
| Cloaking & Metamaterials Testing | TM, TE    | Laboratory waveguide setups                       | 10–100 GHz         |
| EMC/EMI Test Chambers            | TE        | Simulating interference in spacecraft electronics | 0.1–10 GHz         |

RF Shielding and EMC Chambers

⚙️ Application:

Parallel plate setups supporting TE and TM waves are used in designing electromagnetic compatibility (EMC) testing chambers.
EM fields (especially TE modes) help simulate interference for testing electronics used in satellites and deep-space missions.

**⚙️ DEEPER TECHNICAL INSIGHT: TE & TM WAVES BETWEEN PARALLEL PLATES**

🔹 Field Configuration

1. TE (Transverse Electric) Modes

E-field is entirely transverse (no longitudinal component) 

H-field has a longitudinal component

Simplest TE mode: TE₁₀ (used in most rectangular waveguides)

2. TM (Transverse Magnetic) Modes

H-field is entirely transverse (no longitudinal component) 


E-field has a longitudinal component, useful in particle acceleration and sensing


**🛰️ IN-DEPTH APPLICATION:**


VOYAGER 1 COMMUNICATION SYSTEM


⚙️ Waveguide System in Voyager 1:

X-Band High-Gain Antenna (HGA): Transmits data to Earth via a waveguide feed system.

Inside this system, electromagnetic waves are generated and guided using waveguides modeled using TE and TM mode behavior, particularly TE₁₀.

These waveguides connect:

Traveling wave tubes (used for amplification)

Antenna horn feeds

Power-combining and splitting devices (like hybrid tees)

📡 Key reason for TE₁₀ use: It’s the dominant mode with no cutoff distortion and low loss.



## **🔬 Current Research and Evolution** ##

3D-printed parallel plate waveguides for rapid prototyping in aerospace systems.

Use of reconfigurable metasurfaces inside waveguides to dynamically switch between TM and TE modes.

AI-designed waveguide structures for optimized radiation pattern and minimal reflection.





​





