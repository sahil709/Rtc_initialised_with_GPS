# Rtc_initialised_with_GPS
Here i have created a project which sets the time of RTC(clock) using GPS module.

LIBRARY USED:-
1.<Tinygps++> 
2.<RTClib.h> 
3.<wire.h> 
4.<SoftwareSerial.h>

*******************************************************************************************************************************************
Apparatus Required:-
1.RTC Ds3231(clock).
2.Neo-6m GPS module.
3.Arduino Uno.
4.Male-to-Female jumpers.


DESCRIPTION:-
A Gps is used to show the current location,Date ,time,lat,long but using that we can reset rtc so that we can get the accurate time.RTC means Real Time Clock. RTC modules are simply TIME and DATE remembering systems which have battery setup which in the absence of external power keeps the module running. This keeps the TIME and DATE up to date. So we can have accurate TIME and DATE from RTC module whenever we want.Then GPS is used to reset the RTC and convert UTC time to GMT+5.5 according to Indian standred time.This is how time is shows in any smart phone in the world. It is a simple project but gives knowlage about working of GPS,RTC modules in Smartphones.
