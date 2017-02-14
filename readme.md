# Laser Interlock Controller
The firmware for a laser interlock controller with two door switch inputs and two (switched at the same time) relays which are connected to lasers.
In addition the unit has two LEDs on the front panel (one blue and one red), one external LED (which is mounted on a door) , an internal buzzer and an 
over ride keyswitch on the front panel.

* When initially turned on the unit is in inactive mode (blue LED on , relays open).
* If the user turns the keyswitch upwards until the buzzer sounds then turns it down again the unit is in active mode (blue LED off , red LED on and relays closed).
* If the door contacts are opened while in active mode the unit returns to inactive mode.
* If while in active mode the user turns the keyswitch upwards the unit goes into over ride mode (blue LED off , red LED flashing , buzzer sounding and relays closed).
* In over ride mode the door contacts can be opened and the relay remains closed. 
* The constant beeping reminds the user they are in over ride mode.
* To come out of over ride mode the user turns the key switch back to the down position and the unit returns to active mode.

Ian Wraith (14th February 2017)