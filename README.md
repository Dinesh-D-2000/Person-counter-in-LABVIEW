<h1>Person Counter in LABVIEW<h1>
<h2>Introduction</h2>
<img align="right"  src="https://user-images.githubusercontent.com/81762286/113425069-d9c50780-93ee-11eb-8900-7835777c5210.gif">
Many times we need to monitor the people visiting some place like shopping mall. To provide solution for this we are going to implement a project called “Person Counter”. The Basic concept behind this project is to measure and display the number of persons entering/leaving  any room like seminar hall, conference room etc. This works in a two way. That means counter will be incremented if person enters the room and will be decremented if a person leaves the room. By interfacing Arduino with LABVIEW, the no of person entering/leaving a room is counted and displayed.
<h2>Materials used</h2>
<ul >
<li>IR Sensor</li>
<li >Arduino UNO</li>
<li >Bread board</li>
<li >Connnecting wires</li>
  </ul>
<h2 >Software used</h2>
<ul >
<li >NI LABVIEW</li>
 </ul>
<h2 >Working</h2>
  <p>LABVIEW gets the sensor data via a Data Acquisition System(DAQ). In our project arduino UNO serves that need. The number of people entering and leaving a room is displayed in the front panel of the LABVIEW as shown below.</p>
<p align="center">
  <img  src="https://user-images.githubusercontent.com/81762286/113396877-d2373b80-93b9-11eb-8923-c09d3b1ce175.gif">
</p>
<h2 >Conclusion</h2>
In our project we have designed and implemented  bi-directional visitors counter  using labview. The target users of the project can be any one right from a common man to any organization. Lets say if anyone uses our project for seminar purpose then the track record of the persons attending the seminar will give the exact idea about the no. of candidate attending and leaving the seminar and accordingly the project model will control the electronics gadget of the seminar hall.This project can bealso be modified for automatic room light control. It will help to save electricity when no one is there in a room. In school / companies it will help to check if somebody is there in the zone or not. If the data on the display unit is zero the security guard can shut the gate easily.



