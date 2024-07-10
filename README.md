## The Neuromorphic Radar Project
This repository lists all the hardware design files for the neuromorphic radar project. 

Each channel comprises the ILO, the Mixer, and the spike encoder. They can be assembled using SMA connectors. 
![1-channel](https://github.com/kaizheng28/neuro-radar/assets/144567523/aa11b01c-7e67-4b84-a484-f320f9e5c70e)

The base board provides a stable power supply and mechanical structure for up to 6 channels of the NeuroRadar sensor. The assembled single-channel sensor can be attached to the base board through 2.54mm header pins.
![6-channel](https://github.com/kaizheng28/neuro-radar/assets/144567523/88a82930-523f-446b-a855-ca759a44e0f7)


## File Folder Explanation
**NeuroBB**
The basebase processing circuit and the spike encoder.

**NeuroILO**
The self-injection locked oscillator.

**NeuroMIX**
Delay-and-mixing circuit.

**NeuroMother**
The base board for multi-channel neuro-radar.

## Reference
Kai Zheng, Kun Qian, Timothy Woodford, and Xinyu Zhang. 2024. NeuroRadar: A Neuromorphic Radar Sensor for Low-Power IoT Systems. In Proceedings of the 21st ACM Conference on Embedded Networked Sensor Systems (SenSys '23). Association for Computing Machinery, New York, NY, USA, 223–236. https://doi.org/10.1145/3625687.3625788
