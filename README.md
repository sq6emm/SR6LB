This is technical documentation of SR6LB microwave beacon

Meshtastic trace url: [https://lorastats.pl/Node/54034]

# History

+ 2025-05-02 - beacon installed and running, however 23cm reported .816 instead of .830 and 10GHz reported .723 instead of .830, 24GHz reported +300kHz higher - confirmed that GPS is not working
+ 2025-05-05 - reported that 10GHz is down
+ 2025-05-19 - professional GPS antenna connected - beacon has lock and is transmiting digital JT4, 10GHz is still down
+ 2025-05-22 - beacon is DOWN, SR6LHZ / SR6XHZ is operational again, beacon went for maintanance to resolve the 10GHz issue
+ 2025-10-05 - beacon is UP, 10GHz was fixed (it seems there was some cold soldering), Meshtastic was added that is sending telemtry on voltage and current, there is sill issue with GPSDO, no digital mode is transmitted and frequency seems to jump from time to time when GPSDO looses its lock
+ 2025-12-04 - beacon is DOWN, it was identified that there is no power at the beacon (Meshtastic is also not working while its only dependency is 12V)

