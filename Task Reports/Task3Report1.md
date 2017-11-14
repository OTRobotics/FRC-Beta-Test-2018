# Task 3 Part 1/2

1. Note any required changes to your robot program not detailed in the documentation for porting robot code.
	New package for the CTRE Library, but was to be expected.
2. Using the Charts tab of the Driver Station, report the resource usage of your robot code (roboRIO CPU usage, free RAM)
	Had a problem with the new CTRE library with a memory leak - see tracker: https://usfirst.collab.net/sf/go/artf5580?nav=1&_pagenum=1&returnUrlKey=1510675896587
	Had another problem regarding NavX and immense cpu/ram usage - Is an actual wpilib bug: https://github.com/wpilibsuite/allwpilib/issues/733
	Offseason DS Logs from 1334 will be attached.
3. What problems or difficulties did you encounter?
	Above details the major issues we had. Beyond those, no other major issues.
4. What questions did you have during the process?
	None.
5. Any specific suggestions on improving the documentation? (Were any instructions unclear?)
	CTRE Library packaged changed, would be a good documentation point if not alreay noted.
6. Is there anything else you want to tell us related to this task?
	2 bugs from 1 offseason! Woo!
