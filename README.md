# URdancing
This project was developed by MRAC 2021-22 students for the Personable Robotics Workshop (WS 3.2) at the Institute for Advanced Architecture of Catalonia

Students: Alfred Bowles, Grace Boyle, Mit Patel, Libish Murugesan, Andrea Najera
Faculty: Madeline Gannon, Aslinur Taskin, Daniil Koshelyuk

# File Setup

1. Load the touchdesigner file: **ParticleCloudAudio.toe**

Change the path of the "Audio File In" component to an mp3 file path on your computer

Note that this file runs on TouchDesigner 2020 as later versions utilize an updated version of the ParticlesGPU component which is not compatible. The rest of the file can run normally on later versions however there will be o particle visualizations.

2. Run the personable_robotics_osc Rhino file along with the corresponding Grasshopper script

The Rhino file can be found here as it is a large file: https://drive.google.com/file/d/1kBxjpjcbrFfDZ7HiuckwjWLcqWECq7OK/view?usp=sharing

In the grasshopper file make sure that:
- The inputs into the 'Firefly Receive UDP' match the OSC ports being sent from Touch Designer
- The outputs from the 'Firefly Send UPD' match the OSC ports on the robot control software
- The IP addresses are correct
