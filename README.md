Download Link: https://assignmentchef.com/product/solved-cpe-301-lab-02-decoding-d-latches-shift
<br>



<ol>

 <li>To become familiar with the logic required to decode a number of input signals using a decoder and latch circuit, such as in a memory address decoding circuit problem.</li>

 <li>To understand how a shift register works and the various control signals necessary to operate the IC.</li>

 <li>To learn how to read a data sheet and build a circuit from the information found.</li>

</ol>

<u>Required Equipment:</u>

<ol>

 <li>Laboratory Oscilloscope 1K-4.7KΩ SIP Resistor (for switches)</li>

 <li>Laboratory Power Supply DIP 74LS138</li>

 <li>Laboratory Function Generator DIP 74LS373</li>

 <li>DIP Bar Graph LED DIP 74LS164</li>

 <li>DIP 10-position switch array Solderless Breadboard</li>

 <li>DIP Push-button Jumper Kit</li>

 <li>330Ω SIP Resistor (for LEDs) <u>Procedure:</u></li>

</ol>

<strong><u>BEFORE THE LAB</u></strong>: Find the datasheets for the 74LS138, 74LS164, 74LS373 and read their functional descriptions on the first few pages. Then review how a decoder functions.

Complete each part of the lab, answer the questions and include them in your lab report. Be sure to label your answers with respect to their relevant lab part and question number (ex. Part 1 #4c). Any handwritten drawings should be scanned and included alongside the text of your lab report.

Part 1 – Construct a circuit which demonstrates the truth table of the 74LS138 as depicted below.

Connect the switches to the input of the 74LS138 using the pullup resistor configuration you learned in Lab #1. Notify the Lab Instructor when your circuit is complete and demonstrate the circuit for full credit.




1

CPE 301 Lab #1 – Oscilloscopes, LEDs, Resistors and Push-buttons




<ol>

 <li>Briefly explain how the circuit works / what function does it perform in terms of its input and outputs?</li>

 <li>What are the control signals on the 74LS164?</li>

 <li>What are the control signals on the 74LS373?</li>

 <li>Include a picture of the circuit you built while its input is 0b010.</li>

 <li>Draw a circuit diagram in which a 74LS138 is connected to a 6-bit address bus (A<sub>0</sub>-A<sub>5</sub>). The 74LS138 is used to select the Chip Select signals among 8 rangefinders that are mounted on a robot (CS<sub>0</sub>-CS<sub>7</sub>). The range finders are mapped as external data memory at addresses 0x08 through 0x10. Any time the range finder’s address is placed on the 6-bit address bus, the corresponding Chip Select signal should go low.</li>

</ol>

Part 2 – Construct a circuit which demonstrates the functionality of the 74LS164 Shift Register as depicted in the figure below. Use the push button with a pullup resistor to generate the shift in signal. Use a function generator set to a slow frequency, (0.5 to 5hz) as the clock in signal. Notify the Lab Instructor when your circuit is complete and demonstrate the circuit for full credit.




<ol>

 <li>Briefly explain how the circuit works / what function does it perform?</li>

 <li>Include a picture of your circuit while it is displaying 0x55.</li>

 <li>What are the control signals on the 74LS164?</li>

 <li>Draw a timing diagram containing all control signals of the 74LS164 necessary to generate an output of 0x43.</li>

</ol>