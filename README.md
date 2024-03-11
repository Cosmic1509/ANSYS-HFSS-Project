<h1>
  8 Element Dual Band MIMO Antenna System for 5G Mobile Devices
</h1>
The 8 Dual-band MIMO(Multiple Input- Multiple Output) systems can cover in the ranges from (3Ghz to 5.0Ghz) due to this transmission of N77, N78 and N79 5G high transmission can be possible. In this Antenna, there are two resonant modes such as TM01 and TM10 which have values of 0.75λ and 1.0λ. We have figured out that the resonant frequencies between 0.5 λ and 1.0 λ can be excited and result in another new resonant frequency which is 0.75 λ which accelerates the 5G dual-band transmission in mobile phones. We can achieve a dual-band antenna using the coupling techniques for loop antennas with these modes. The dual-band MIMO system can achieve impeccable results in mobile phones which has led to the genesis of certain 5G transmission. The characteristics we calculated are antenna isolation, envelope correlation coefficient (ECC) and Chanel Capacity (CC). We have designed a MIMO model on Ansys HFSS Software with 8 antennas on two clearance areas of the substrate, which has 50-ohm microstrip lines as the feed which is parallel to the plane and the SMA Coaxial Cable Connector is perpendicular to the ground of the antenna connecting to the feed line and to the ground, due to this we can observe maximum radiation transmission in two resonance modes such as 0.75λ and 1λ which gives us a dual-band transmission for mobile phones and no Efficiency Degradation when the system is held by hand.


<h3>
DIMENSIONS OF THE PROPOSED DUAL-BAND MIMO SYSTEM:
</h3>

 The dual-band 8 MIMO system can cover (3.3GHz to 5.0GHz) and has 8 antennas which are arranged along the edges of the mobile terminal. The dimension of the entire system substrate is 150mm×75mm× 0.8mm. The two clearance areas are (75mm×8mm). There are two small substrates which are on each side of the main substrate, these two small substrate’s dimensions are 134mm×6mm×0.8mm and have 4 antennas connected on each side. The 4 antennas are of two different coupled loop antennas which help for wideband transmission. The antenna strip height and width are 6mm and 1mm. The placement of the four antennas are is quite intricate where each antenna length is either 22mm or 21.5mm, the distance between the antennas Ant1 to Ant2, Ant2 to Ant3 and Ant 3 to Ant 4 are d12, d23 and d34. The Distance between the feed lines of each antenna is D12, D23 and D34. 
As seen at the outcome of the MIMO system, it has been proposed that if the length of the first antenna is kept at 22mm we have seen a massive increase in the antenna’s total efficiency as the frequency 3.3GHz increases from 36% to 65% when L varies from 21mm to 22mm.

 ![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/644af3f6-5236-4b19-a78d-a0ae56c27848)

<h3> 
PROBLEM DEFINED:
</h3>
In particular, the proposed wideband 8-antenna MIMO system shows quite high isolation, low envelope correlation coefficient, and good channel capacity, which are all good enough for practical 5G MIMO antenna application in mobile terminals. 

MIMO Model:

![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/151a2de4-eb57-4fa2-8fa3-1cdc0ad941ae)

<h3> 8 ANTENNA DUAL-BAND MIMO SYSTEM USING COAXIAL FEEDS AND DIFFERENT RESONANT FREQUENCIES: </h3>

Multiple-Input Multiple-Output (MIMO) is a wireless technology that uses multiple transmitters and receivers to transfer more data at the same time. 
MIMO technology uses a natural radio-wave phenomenon called multipath. With multipath, transmitted information bounces off walls, ceilings, and other objects, reaching the receiving antenna multiple times at different angles and slightly different times. In the past, multipath caused interference and slowed down wireless signals. With multipath, MIMO technology uses multiple, smart transmitters and receivers with an added spatial dimension, increasing performance and range.
In the proposed coupled-loop MIMO antenna system, the system consisting of only one single antenna element will be considered first. The detailed dimension and configuration of the single antenna unit or element (Ant1). This antenna unit contains four radiating branches: two inner branches and two outer branches. The inner and outer branches are located on the inner and outer surfaces of the small PCB, respectively.

The antenna is fed at one end of the left inner branch and grounded at one end of the right outer branch. The four branches are symmetrically located (except they are located at the two different surfaces of the small PCB) along the central line of the antenna element. There are three overlapped sections between the four branches: one of them is located at the top centre of the antenna and two of them are located at the left and right sides of the antenna;

These two modes of the proposed coupled-loop antenna are 3.50GHz and 4.50GHz. One can know that the first resonance (3.50GHz) mode of the coupled-loop antenna works as its 0.75λ mode. One can conclude that the proposed coupled-loop antenna can support its 0.75λ and 1.0λ modes, whereas the other loop antennas support its 0.5λ, 1.0λ and 1.5λ modes.
 Most importantly, the two resonance modes, i.e., the 0.75λ and 1.0λ modes, can widen the bandwidth of the coupled-loop antenna. This wider bandwidth works very well in the frequency range of 3.3-5.0GHz, which can cover all the 5G N77, N78 and N79 bands.
	The antenna comprises of 8 antennas which are placed in the inner and outer regions of the small side substrate. These antennas are to be of accurate dimensions and lengths in order to obtain the dual-band. All the lower inner antenna branches are connected to the feed line which is of the same material and are united, further the lower outer branch is grounded to the ground which is placed below the substrate. This gives us the two resonant modes TM01 and TM10 which is of resonant modes 0.75λ  and 1λ.
There is a overlap of 1.5mm in the lower and upper antenna overlap and there is a 10mm overlap in the two upper antennas. On one small side there are two top coupled antennas and two two-side antennas. The parameters bring out an efficient transmission of the antennas and gives us a dual-band, which is very useful in mobile devices.

The coaxial cables are added to every coupled loop antenna perpendicularly to the surface, where the feed line is 50 ohms and an excitation which is a wave port is supplied to the coaxial cable bottom edge. The coaxial cables enhance the transmission. First we must drill a hole for the coaxial cable from the substrate, once this is done an outer shell is created for the coaxial cable of a radius of 0.5mm and from the substrate bottom to a certain length (5mm). Further, the inner coax is given a radius of 0.25mm and from the bottom of the substrate to 5mm. and another inner coax is given a radius of 0.25 from the substrate to the feedline. This gives us a coaxial cable for the feedline which is assigned a Lumped port at the bottom of the coaxial cable, this lumped port enables us to give an input impedance of 50ohms. Each and every antenna’s feed is assigned a coaxial port which leads to efficiency and dual-band transmission and optimum 50ohms impedance.

After designing the model of our 8 dual-band MIMO system, we have assigned the boundaries and excitations of our model in order to make our model work like a real antenna within the software, where we can observe the outputs.
The materials that have been assigned are :
1.	The substrate is given a material of the name FR4_epoxy where this material is The proposed antenna has been designed using Flame Retardant 4(FR4) substrate of dielectric constant ℇr= 4.4 and is placed in between the copper patch and ground plane.
2.	The small side substrates, antennas, feedlines, wave-ports, inner coax and ground are made of perfect Electric conductor.
3.	The Radiation box is given the dimensions of 360mm x 280mm x 80mm, whose faces are assigned radiation material and the bottom part of the radiation box is not assigned.

2.	We must check whether our designs boundaries, model and excitations have any errors or not, hence we must validate our model and further analyze all the conditions. Then our model will get simulated.

3.	Once the simulation is done, we must create a new analysis for our results, adding the appropriate parameters, we can plot a rectangular plot or far-field plot for our model. Identify the resonant frequencies for the wave-ports of each feedline antenna and we can see that we have obtained a dual-band at the output.

	After looking at the outputs we can observe the dual-band for all the antennas which have wave-ports, this indicates that our dual-band 8-antenna MIMO system has not only good isolation but also good antenna total efficiency which is excellent for mobile device transmission.


ALL ANTENNA TRANSMISSION GRAPHICAL REPRESENTATION

 

Figure 1) Antenna Design in HFSS


![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/52038ae2-f3e5-4e7b-a576-eda0f6b8994f)

 

Figure 2) Antenna model with radiation box

![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/ffe3f397-8160-4c92-be44-1f59a2b7c62e)

 

Figure 3) Antenna system, feedlines and coax cables


![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/3df80db6-3d9d-49dd-a8b5-8e1bbc84c04f)


 

Figure 4) Inner view of antenna 1


![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/cad76769-3772-4aa2-890c-456f1e026b23)



 

Figure 5) Outer view of antenna 1

![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/890d8e6b-9c3a-4941-8ee7-1c2244d53e8d)


 

Figure 6) Coax Cables of the antenna 



![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/0ebf9886-d530-4be5-adcc-bc89eca25408)



 

Figure 7) Antenna Wave-port 1 output wave, we get a dual-band



![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/d2e7eb84-b5d2-42de-a445-34ad1e71f267)


 


Figure 8) Outputs of Antennas 1 to 8; where all are dual-bands


![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/ff83d337-5cca-46ee-8290-2db931e70d6b)

 

Figure 9) SWR of antennas and antenna waveport outputs combined 


![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/f1a3cc66-241f-48a8-945e-52be3913a497)


 

Figure 10) SWR of antennas and antenna waveport outputs combined with curve info 

![image](https://github.com/Cosmic1509/ANSYS-HFSS-Project/assets/82835887/9c39e77e-2ca7-4114-aa9d-239775ad80c6)


<h3>CONCLUSION:</h3>
A dual-band 8-antenna MIMO system that can cover the 3.3-5.0GHz band is proposed for the 5G application in mobile terminals. Particularly, the MIMO antenna system is based on a coupled-loop antenna element with three coupling sections in its radiating branches: one on the top centre and two on the left and right sides. The frequencies obtained are 3.50Hz and 4.50Hz, most importantly, due to the above special arrangement, a new resonance mode the first resonance (0.75λ) mode of the loop antenna is generated for the first time. As a consequence, the combination of this new mode of the loop antenna makes the bandwidth of the proposed coupled-loop antenna a dual-band, which can cover all the 5G N77, N78 and N79 bands.
The performance of the 8-antenna MIMO system is confirmed by both simulation and measurement, and good MIMO antenna performance is obtained. In particular, the proposed dual-band 8-antenna MIMO system shows good isolation due to the feeding mechanism used and, the envelope correlation coefficient is quite accurate with its counter antennas, and good channel capacity, which is all good enough for practical 5G MIMO antenna application in mobile terminals.

