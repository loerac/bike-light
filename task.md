# Task
- [x] TID #SW000 - Figure out the language
 * ~~Python~~
 * C++
 * ~~Go~~
 * ~~C~~
 * ~~C#~~

- [ ] TID #HW000 - Figure out what type of board we want to use
    - [ ] LEDs
      * Neopixel ring
      * Circut Playground
      * Neopixel stick
      * Flora RGB Neopixels
    - [ ] Microcontroller
      * Teensy board
      * Circuit Playground (Comes with LEDs and accelerometer)
    - [ ] Accelerometer
      * Flora accelerometer
    - [ ] GPS
      * Flora GPS module

- [x] ~~TID #002 - Add a button/switch for brake~~
 * ~~When the brakes on the bike are pressed, turn the brake lights on~~

- [ ] TID #SW001 - Light Indicator
  * When idle/cruising, the idle/cruising lights shall be on
  * When braking, the braking lights shall be turned on

- [ ] TID #SW002 - Calculate Acceleration
  * Given two coordinates, calculate the distance between them over a certain period of time.
  * Figure out a good amount of time to calculate the distance (0.25 second, 0.5 second, 1 second, 2 second???)

- [ ] TID #SW003 - Calcuate Position
  * Given the current position of the bike (flat, up-hill, down-hill), calculate the new threshold of braking
  * There shall be a constant threshold for flat, and the threshold will be updated once the bike position is going up/down-hill

- [ ] TID #HW001 - Add a power switch and battery to the board
  * Coin battery or lithium battery?

- [ ] TID #HW002 - Add indicator onto the bike
 * We don't want water getting into the circut board or button/switch, should have a case to protect
 * We don't want the circut board to fall or get worn off on the bike
