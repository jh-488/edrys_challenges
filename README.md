# Edrys challenges
A couple of challenges for [Edrys-Lite](https://edrys-labs.github.io).

To create a classroom with a challenge, just click the deploy button of the desired challenge.

To use your machine as a station, you need to run the [Edrys Server](https://github.com/jh-488/edrys_server) locally.

## Turn-On-Led-001
A simple challenge where the student has to turn on the built in LED of the board.

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/jh-488/edrys_challenges/main/turn-on-led-001.yml)

Required arduino libraries : [ArduinoUnit](https://github.com/mmurdoch/arduinounit)

## Turn-On-Led-001(with-timer)
The same challenge as Turn-On-Led-001, but with a timer. The student needs to solve the challenge before the time ends.

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/jh-488/edrys_challenges/main/turn-on-led-001(with-timer).yml)

Required arduino libraries : [ArduinoUnit](https://github.com/mmurdoch/arduinounit)

## Turn-On-Led-001(Multiplayer)
A multiplayer mode for the Turn-On-Led-001 challenge. Multiple students can gather in a room and the first one to solve the challenge wins.

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/jh-488/edrys_challenges/main/turn-on-led-001(multiplayer).yml)

Required arduino libraries : [ArduinoUnit](https://github.com/mmurdoch/arduinounit)

## Missing-Led
After starting this challenge, 2 LEDs out of the 3 will be turned on. The student need to write a program that will turn on the missing one and turn off the other 2 LEDs.

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/jh-488/edrys_challenges/main/missing-led.yml)

Required arduino libraries : [ArduinoUnit](https://github.com/mmurdoch/arduinounit)

## Snake-Game
A fun game where the student need to modify the given code to display an item on the LED Matrix and move the snake to eat it.
If the item is eaten, a happy face will be displayed on the LED Matrix. If the snake hits itself or the borders a sad face will show.

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/jh-488/edrys_challenges/main/snake-game.yml)

Required arduino libraries : [LedControl](https://wayoda.github.io/LedControl/)