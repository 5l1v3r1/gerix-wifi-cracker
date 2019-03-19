
Gerix Wifi Cracker v3.1

REQUISITES:
-----------------------------------------------------------------------------------------------
Dependencies (this tools assume you run Kali):
apt-get install qt4-dev-tools pyqt4-dev-tools python


LAUNCH:
-----------------------------------------------------------------------------------------------
To launch the program use:
$ python gerix.py


TODO
-----------------------------------------------------------------------------------------------
* Add "WPS" attacks with support for both "reaver", "bully" and pixiewps.
* Add WPA handshake attack vector.
* Switch from python2 to python3 (i will need some help with this one)
* Switch from QT4 to QT5 (this to perhaps)

* Change from "iwconfig" to "iw" or "ip" to get the information,
  Line #136 in "gerix_config.py"

  "if exec_command('iwconfig 2>&1 | grep 802.11 | grep' + interface):"

* Add an update checker.




NOTE:
-----------------------------------------------------------------------------------------------
For copy and paste in xterm windows you can use the shortcuts CTRL-INS
and SHIFT-INS.
In alternative, you can select the text with the mouse, and use the third
button of the mouse to paste it. On a laptop you can emulate the third button
pressing the first and the second button together.



