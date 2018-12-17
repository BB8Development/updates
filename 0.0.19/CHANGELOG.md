0.0.19
------
Update Sensory license.

0.0.18
------
Add the ability to set the speak animation delay runtime via LinenAppConfig.json.

0.0.17
------
Add speaking animation.
Change to wait for ACKs between messages rather than sending messages at fixed intervals.

0.0.16
------
Rework animation preempt logic.
Get rid of stray agitation animations after stopping.

0.0.15
------
Add washing and thinking animations.

0.0.14
------
Fix an error in the update script.

0.0.13
------
Fixed a bug which caused a crash when other skills were invoked.
Added a "alsaRecordVolume" parameter to LinenAppConfig.json that is consulted by the run script.

0.0.12
------
Fix more grief in run script.

0.0.11
------
Fix error in run script.

0.0.10
------
Added sending commands for most load types, spin types, water temperatures, drying mode. Added ability to disable updates.

0.0.9
-----
Make play/pause button machine-state aware.

0.0.8
-----
Added detection of door lock state to prevent open when locked.

0.0.7
-----
Use API 144 messages.

0.0.6
-----
Changes to WIN timing and command for start.

0.0.5
-----
Add voice start/stop.

0.0.4
-----
Add play/pause button functionality.

0.0.3
-----
Add the "node" configuration parameter.

0.0.2
-----
Remove amizer call in startup script.
Move display of welcome animation until after AVS is connected.
Add a sound when the startup script starts running.

0.0.1
-----
Fixes the error where TELEMETRY is not recognized as a debug level.
