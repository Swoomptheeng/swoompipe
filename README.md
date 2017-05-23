# maker_monday
Arduino files containing code relating to the Maker Monday Commission.
More on the project at http://swoomptheengs.tumblr.com

The 'Swoompipe' is a weird MIDI bagpipe. It's squeezable (via Flex Sensor), blow-into-able (via Electret Mic), tilt-sensing (via Accelerometer) and playable with 12 Capacitive Keys. 

It's being developed by Ben Neal (www.psiconlab.co.uk) for Swoomptheeng (www.Swoomptheeng.com) as part of a Birmingham City University Maker Monday Commission.


v1. Uses flex sensor, electret mic & capacitive Keys over USB

v2. Uses adds an accelerometer/gyroscope

v3. Uses swaps USB for Bluetooth communications and looses the flex sensor


This system runs connects to a Windows laptop and uses the Hairless MIDI Serial (http://projectgus.github.io/hairless-midiserial/) to capture serial data over USB or Bluetooth COMM ports from the Arduino and sends it to the BeLoop virtual MIDI driver (http://www.nerds.de/en/loopbe1.html) which controls music software and games via the MIDI protocol.
