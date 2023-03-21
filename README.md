# Coin Counter with LCD Display
<h2>Description</h2>
This is a simple Arduino program that counts coins and displays the count on an LCD display using the I2C protocol.<br>
<b>Project at Tha Luang Cement Thai Anusorn Technical College (2017)</b>
<h2>Prerequisites</h2>

- Arduino board<br>
- I2C LCD display (20x4)<br>
- Four push buttons<br>
- Jumper wires<br>
<h2>Installation</h2>
<h4>1. Connect the I2C LCD display to the Arduino board using the following connections:</h4>

- SDA pin of the LCD display to A4 pin of the Arduino board<br>
- SCL pin of the LCD display to A5 pin of the Arduino board<br>
- VCC pin of the LCD display to 5V pin of the Arduino board<br>
- GND pin of the LCD display to GND pin of the Arduino board<br>

<h4>2. Connect the push buttons to the following digital pins of the Arduino board:</h4>

- C1 button to pin 2<br>
- C2 button to pin 3<br>
- C5 button to pin 4<br>
- C10 button to pin 5<br>

<h4>3.Upload the sketch to the Arduino board using the Arduino IDE.<br></h4>
<h2>Usage</h2>
After uploading the sketch to the Arduino board, the program will count the number of coins inserted into each slot and display the count on the LCD display. The LCD display will show the following information:<br><br>

- Coins1 = C[number of 1-cent coins inserted]
- Coins2 = C[number of 2-cent coins inserted]
- Coins5 = C[number of 5-cent coins inserted]
- Coins10= C[number of 10-cent coins inserted]

To insert coins, simply press the corresponding push button for each coin slot. The program will automatically increment the count for that coin.
<h2>License</h2>
This code is licensed under the MIT License. See the LICENSE file for details.
