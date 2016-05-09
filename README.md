# virl-iwan

A VIRL iWAN topology to be used for studying, learning, etc....

Following the Cisco Design Gudies as closely as possible.  There are some things I've intentionally ommitted to focus on the iWAN technology.  For example there is no IPSec encryption configured, no EIGRP authentication and a few other things.  I'm not against putting them into the VIRL topology for completeness, but they are not on the top of my list as they are not core to learning the iWAN concepts.

## Cisco Design Guides
 
 * [Intelligent WAN Technology Design Guide](http://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/Feb2016/CVD-IWANDesignGuide-FEB16.pdf).
 * [Intelligent WAN Configuration Files Guide](http://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/Feb2016/CVD-IWANConfigurationFilesGuide-FEB16.pdf).

## Notes:

* To generate specific types of traffic use the linux 'server' images at each remote site.  
	e.g. `ping -Q <TOS> <host>`


| TOS (decimal) | DSCP Class    |
| ------------- |:-------------:|
| 0 			| be 			|
| 32			| cs1			|
| 40			| af11			|
| 48			| af21 			|
| 56			| af13 			|
| 64			| cs2 			|
| 72			| af21			|
| 80			| af22			|
| 88			| af23 			|
| 96			| cs3 			|
| 104			| af31 			|
| 112			| af32 			|
| 120			| af33 			|
| 128			| cs4 			|
| 136			| af41 			|
| 144			| af42 			|
| 152			| af43 			|
| 160			| cs5 			|
| 184			| ef 			|
| 192			| cs6 			|

##  Contributing

There are lots of tasks still remaining to be completed, so please feel free to fork and submit a pull request.  I am actively working on making this more complete and as much like the design guides listed above as I can, but sometimes my day job gets in the way of personal endeavors.  

