# raspberry_pi_rf_workspace

Messing around with RPI and 433 MHz signal.  

Download `pip install rpi-rf`

`rpi-rf` has two built in scripts: one for receive and one for sending signals.

NOTE: Make sure to look at the `#!` in each script and that it's pointing to
the desired Python source.

## Guides

<https://www.instructables.com/Super-Simple-Raspberry-Pi-433MHz-Home-Automation>
<https://www.princetronics.com/how-to-read-433-mhz-codes-w-raspberry-pi-433-mhz-receiver>
<https://www.youtube.com/watch?v=Xe5Bj_N4Crw>
<https://domoticproject.com/controlling-433-mhz-remote-raspberry-pi>

## Project log

### 20 Aug 2022

Hooked up RPI Zero to 433 receiver but could not get signal.  
The only output was a code "2".  Tried with various remotes but the remotes
are likely to be IR.  Tried with car keys but did not produce expected result.
