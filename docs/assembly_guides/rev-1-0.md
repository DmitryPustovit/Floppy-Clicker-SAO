# Revision 1.0
![Revision 1.0 Board](../images/revison_1_board.png)

### Bill of Materials:
1. Floppy Clicker Rev 1.0 Board (pre-programmed)
2. 3v Relay (Some debug kits had 5v but were provided with 2 CR2032 batteries)
3. Buzzer/Speaker
4. LEDs
    - 1 Red
    - 1 Green
5. Tactile push button
6. CR2032 battery holder (Double sided sticky tape on back)
7. 2 Wires for battery holder
7. Male SAO connector (2x3 pin header)

### Assembly Notes:
- **Buzzer/Speaker should be mounted on top with positive facing up towards MCU**
  - It was discoverd that the buzzer/speaker did not allow SAO to be securely attached to badges for some badges. (Like the Supercon Communicator Badge)
- LED Anode (positive) goes to the circle pad
- Battery holder top rectangle pad is positive

### Assembly Steps:
1. **Button**:
    - Solder button onto the board
    - It should only fit one way
   
2. **LEDs**:
    - ⚠️ **Important**: LED Anode (positive/long leg) goes to the **circle pad**
      - LED Cathode (negative/short leg) goes to the square pad
    - Green LED is for power (Bonus points if you know what computer this is a reference to.)

3. **Relay**
    - ⚠️ **Important** This version of the board does not use the correct footprint for the *TODO: Insert relay name.*
