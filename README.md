RoboKitty
=========

Arduino UNO codebase for a robotic kitty. <br>
Currently not accepting code commits from public users.<br>

Current Modules/Features

<table>
  <tr>
    <td>Feature</td>
    <td>Module(s)</td>
    <td>Hardware</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>8bit Radio</td>
    <td>EightBitRadio</td>
    <td>1 Pezo</td>
    <td>
      Plays 8bit tunes that are hardcoded into the module.<br>
      <br>
      Tunes include: <br>
      - Mario Overworld Theme (partial tune)<br>
      - Zelda - Turtle Rock<br>
      <br>
      Settings that can be changed from within module code:<br>
      - On/Off: turns the radio on/off.  currently a useless setting.<br>
      - Loop: whether a tune will restart after finishing (if not, continues to next song in playlist)<br>
    </td>
  </tr>
  <tr>
    <td>Battery Monitor</td>
    <td>BatteryMonitor</td>
    <td>10 LEDs, 1 Battery</td>
    <td>
      Displays the remaining charge of the attached battery in increments of 10%, with each of the 10 LEDs corresponding to a single increment range.  All LEDs up to calculated remaining percent will display a solid colour, while the LED representing the current percent blinks.<br>
      Example: At 56% remaining charge, LEDs 1-5 will light up (they represent the range from 0%-40%), and LED 5 will be blinking since 56% lies in the 50%-60% range.
    </td>
  </tr>
</table>
