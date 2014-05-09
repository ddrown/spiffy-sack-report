This program will show individual tcp flows for a given mac address.  See the file 'example' for an example of how to run it

Example output (current state is printed once per second):

	2605:6000:xxxx.22 => 2602:3f:xxxx.49598 pkt=11 loss=0% speed=2.5Kb/s, pkt=11 loss=0% speed=0.0b/s

	2605:6000:xxxx.22 => 2602:3f:xxxx.49598 pkt=14 loss=0% speed=4.0Kb/s, pkt=15 loss=0% speed=832.0b/s

	2605:6000:xxxx.46198 => 2600:3c00:xxxx.80 pkt=163 loss=0% speed=912.0b/s, pkt=262 loss=0% speed=3.0Mb/s
	2605:6000:xxxx.22 => 2602:3f:xxxx.49598 pkt=18 loss=0% speed=6.5Kb/s, pkt=21 loss=0% speed=560.0b/s

	2605:6000:xxxx.46198 => 2600:3c00:xxxx.80 pkt=218 loss=0% speed=456.0b/s (final), pkt=358 loss=0% speed=2.0Mb/s
	2605:6000:xxxx.22 => 2602:3f:xxxx.49598 pkt=25 loss=0% speed=6.2Kb/s, pkt=28 loss=0% speed=373.3b/s

	2605:6000:xxxx.22 => 2602:3f:xxxx.49598 pkt=28 loss=0% speed=7.3Kb/s, pkt=31 loss=0% speed=280.0b/s
	2600:3c00:xxxx.80 => 2605:6000:xxxx.46198 pkt=358 loss=0% speed=1.3Mb/s (final)

From this output, you can see there was a ssh session and a http download.  The HTTP download ended at a rate of 2.0Mbit/s
