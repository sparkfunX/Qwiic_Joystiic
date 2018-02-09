# Qwiic_Joystiic
Thumbstick Breakout for the Qwiic System
<br/><br/>
Factory Default I2C Slave Address: 0x20<br/>
<br/>
<u>I2C Registers</u><br/>
0x00-0x01 Horizontal Position (MSB First)<br/>
0x02-0x03 Vertical Position (MSB First)<br/>
0x04 Button Position<br/>
0x06 Current I2C Slave Address from EEPROM<br/>
<br/>
<u>I2C Commands</u>
0x05 Set I2C Slave Address
