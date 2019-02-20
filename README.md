Assistive Fightstick

    This project aims to create firmware for a "Fightstick" (a gaming controller that consists of an arcade joystick and several arcade buttons, normally used to allow gamers to play fighting games in the same way one would if they were playing on an arcade machine on their own PC or gaming console).  Instead of using the standard "joystick on left, buttons on right" fightstick layout, the buttons are layed out in an arc from roughly 10 o'clock to 4 o'clock, centered around the joystick.  The joystick functions as "WASD" and the buttons take the place of the 6 most common keyboard keys for FPS gaming, effectively taking the place of a keyboard in a normal keyboard-and-mouse gaming setup.  This allows a person with an injured left hand to continue to game with a minimal amount of remaining dexterity.

    The original controller was built using an Arduino Leonardo (ATMega 32u4 microcontroller), but because the Leonardo was discontinued by Arduino, the code is being ported for use with the Teensy 3-series (Teensy 3.0/3.1/3.2 and Teensy LC).  The code to utilize the Teensy microcontroller dev boards is a work-in-progress, but if you have an ATMEL ATMega 32u4 dev board that is compatible with the Arduino IDE, the code should be perfectly useable as long as you set up the pinout variables correctly.

Authors

    Matt Stanton
    Jason Bunn

License

    This code is provided freely with the only stipulation being that any copies or derivative works include attribution in the form of a link to: https://github.com/N0BOX/Assistive_Fightstick
