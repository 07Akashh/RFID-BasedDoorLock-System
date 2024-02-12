# RFID-BasedDoorLock-System

## Overview

This project implements an RFID-based door lock system using Arduino Uno, a solenoid lock, RFID module, relay module, jumper wires, buzzer, and red/blue LEDs. The system is designed to secure access to a door by authenticating users with RFID cards or tags. The solenoid lock is controlled by the Arduino Uno, which communicates with the RFID module to verify user credentials.

### Components:

- **Arduino Uno:** Connect to the power source (5V, GND).
- **Solenoid Lock:** Connect to the relay module.
- **RFID Module:** Connect to digital pins on the Arduino (TX, RX).
- **Relay Module:** Connect to digital pin on the Arduino (D2).
- **Buzzer:** Connect to digital pin on the Arduino (D3).
- **Red LED:** Connect to digital pin on the Arduino (D4).
- **Blue LED:** Connect to digital pin on the Arduino (D5).

## Wiring Diagram

Include a wiring diagram in this section to guide users on how to connect the components. Use clear labels and colors for easy understanding.

### Wiring Instructions:

1. Connect the positive (+) and negative (-) terminals of the solenoid lock to the relay module.
2. Connect the relay module to digital pin D2 on the Arduino.
3. Connect the TX and RX pins of the RFID module to the corresponding digital pins on the Arduino.
4. Connect the positive (+) and negative (-) terminals of the buzzer to digital pin D3 on the Arduino.
5. Connect the positive (+) and negative (-) terminals of the red LED to digital pin D4 on the Arduino.
6. Connect the positive (+) and negative (-) terminals of the blue LED to digital pin D5 on the Arduino.

Ensure proper power supply to the Arduino Uno. Refer to the wiring diagram for a detailed illustration of the connections.

## How to Use

1. **Hardware Setup:**
   - Connect the components based on the provided wiring diagram.
   - Ensure proper power supply to the Arduino Uno.

2. **Arduino Code:**
   - Upload the Arduino code (`arduino_code.ino`) to the Arduino Uno using the Arduino IDE.

3. **Testing:**
   - Place an RFID card or tag near the RFID module.
   - Observe the LEDs and listen for the buzzer to indicate authentication status.
   - The solenoid lock should unlock upon successful authentication.

## Customization

Feel free to customize the Arduino code to add more features or modify the authentication process. Update RFID card IDs and tweak the buzzer and LED feedback based on your preferences.

## Contributing

Contributions are welcome! If you have improvements or additional features to suggest, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
