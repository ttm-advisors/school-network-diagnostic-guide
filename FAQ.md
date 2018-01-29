# Frequently Asked Questions

* [What is "bandwidth"?](#what-is-bandwidth)
* [Where does bandwidth for schools come from and is there enough to go around?](#where-does-bandwidth-for-schools-come-from-and-is-there-enough-to-go-around)
* [How does it get to a school building?](#how-does-bandwidth-get-to-a-school-building)
* [Why are wired connections used to connect schools?](#why-are-wired-connections-used-to-connect-schools)
* [How much last-mile bandwidth does the school building need?](#how-much-last-mile-bandwidth-does-the-school-building-need)
* [How do you get the internet in the school building to the students who want to use it?](#how-do-you-get-the-internet-in-the-school-building-to-the-students-who want-to-use-it)

### What is "bandwidth"?
Bandwidth is a measure of internet speed -- the amount of information or data (specifically bits -- the 1s and 0s) that can come to a computer from the internet \(download speed\) and from a computer back to the internet \(upload speed\).

Internet speed is calculated based on how many bits a connection can carry per second. "Bits" are the individual 1s and 0s are most fundamental unit of all digital communication.

Mbps stands for megabits per second and is a common unit used to measure the speed of internet connections. 1 Mbps is equal to 1,000,000 bit per second. Slower network connections may be measured in Kbps (Kbps) - 1,000 bits per second. Very high speed connections will be measured in gigabits per second - 1 billion bits per second.

Conversions and examples:
* 1 Gbps = 1000 Mbps = 1,000,000 Kbps = 1,000,000,000 bps.
* Dial-up modems used to connect to the internet in the 1990s were usually 14.4kbps or 28.8kbps
* Early first generation "high speed" DSL and cable modem services were in the area of 500kbps to 1Mbps (1000kbps).
* A standard speed offered by Verizon's home FIOS internet service is 100 Mbps, approximately 100x faster than the first generation "high speed" internet services of 20 years ago.
* Some companies (e.g., Spectrum) now offer 1 Gbps home service.

### Where does bandwidth for schools come from and is there enough to go around?
New York City, given its prominent global stature, is generously supplied with bandwidth to the city. Internet bandwidth comes through the physical lines, owned by large global telecoms, that pass under the Hudson and East Rivers. These telecoms in turn sell internet access to homes and businesses. Some telecoms also choose to resell/wholesale bandwidth to smaller internet service providers who work directly with home and business end users.

The internet traffic for devices of the administrators, teachers, and students working and studying in the 1,300 buildings that comprise the NYC DOE physical plant is routed, like a funnel, through one gateway to one of these private internet service providers. The DOE recently completed a [bid process](https://a856-cityrecord.nyc.gov/RequestDetail/20170614013) for a new internet service provider to increase total gateway capacity from 24Gpbs to 240Gbps, a 10x increase. Lightower won the contract in late 2017 and is in the process of doing its upgrade.

### How does bandwidth get to a school building?
The problem with internet access to schools really starts with getting enough bandwidth into the school building itself. There are two components to how internet traffic gets from from the DOE's internet gateway (provided now by Lightower) to a school:

* First, internet traffic travels from the DOE's internet connection (Lightower) into large capacity fiber optic wires, leased by the DOE. These lines create a "ring" across the city that connect seven Department of Education "nodes" located around the five boroughs. A node is a meeting point of network connections, much like the the joints that might connect different water pipes in a plumbing system.

* Second, traffic travels to schools whichever of these seven nodes on the ring is geographically closest to their building. The traffic the closest node to the school building travels through a wired connection, called a circuit, provided by either Verizon or Lightower. This connection from the school building to the closet DOE "node" is sometimes referred to as the "last mile" (and the problem of getting enough bandwidth through that connection the "last mile problem"). The speed of this connection may range from 10 Mbps to 100 Mbps.  The DOE is currently in the process upgrade all circuits in the city to each school building to 100Mbps for single school campuses, 150 Mbps for shared campuses.

Together - the city's ring and its 7 nodes, as well as the individual circuits used to nodes on the ring to school buildings, are sometimes collectively referred to as the DOE's "Wide Area Network" ("WAN"), especially to distinguish these two components from the both the public internet and well as schools internal networks (Local Area Networks - "LANS", which are discussed in questions further down).

### Why are wired connections used to connect schools?
Given the concentration of buildings and obstructions in New York City coupled with bandwidth requirements, wireless technologies are not yet practical at the price appropriate for connecting schools to the DOE within the city, despite the recent evolution in high bandwidth wireless technologies. An exciting development worth watching too is mesh networking, which uses low power, short distance wireless connectivity that is less dependent on a central connection point. For the foreseeable future though last mile wired connections will be the norm.

### How much last-mile bandwidth does the school building need?
If you have only enough [water](networking-analogies.md) to run your sink but not your sink and your toilet, you don’t have enough water coming into the house. The same holds true for bandwidth to the internet - just as there needs to be enough water pressure for each toilet and shower, there needs to be enough internet - enough bandwidth - to serve everyone who wants to use it in a school building.

How much bandwidth is needed in a school? A common refrain is that all schools need "high speed internet" or "broadband". [Until 2015 the FCC definition on "high speed" was 4Mbps](https://www.nbcnews.com/tech/internet/faster-internet-fcc-sets-new-definition-broadband-speeds-n296276) when the [FCC definition was upgraded to 25Mbps](https://www.fcc.gov/reports-research/guides/broadband-speed-guide).

 The FCC also provides some guidelines for how much bandwidth is required for various common internet uses, including
* "General Browsing and Email - 1 Mbps"
* "File Downloading - 10Mbps"
* "Streaming Standard Definition Video - 3-4 Mbps"

As context before 2007 the NYC DOE used an older technology to provide last mile connections (called "Frame Relay"). In 2007 the DOE started the process of upgrading its last mile connections with newer technology to bring schools to a total bandwidth of (at least) 10 Mbps. This target has since been revised to a target of 100 Mbps per school, 150 Mbps, and schools' last mile connections are in the process of being upgraded.

Back to the question of if there is enough bandwidth. Based on the FCC guidelines let's assume in a single school the following:
* 10 administrators are using the network for email and general browing (10 x 1Mbps = 10 Mbps)
* 30 students are downloading files for a science project (10 x 30 = 300 Mbps)
* 20 students in a lab are viewing a streaming video portion of an online literacy program (20 x 4 = 80 Mbps)
The total required bandwidth for this very modest usage scenario is 390 Mbps, nearly 4x to the target for individual school bandwidth.

What are the implications of the aggregate bandwidth exceeding what's available? It’s not unlike if you have only one sink or shower in your house, or worse yet only one toilet.  If everyone has to “go” at the same time, someone is going to have to wait. In the case of actual schools and networks, administrators will probably not notice much lag as they use email. However the lack of enough bandwidth does mean that students downloading files will spend more time waiting and hence less time on task. Some students' file downloads may time out causing them to have to restart downloads, wasting still more time. The students watching video lessons will experience buffering that both distracts from the presentation and makes the video take longer than planned. We've each probably experienced something similar when too many people try and use hot water at the same time in a house -- someone ends up with a cold shower.

### How do you get the internet in the school building to the students who want to use it?
Assuming there is enough internet (\(enough "bandwidth"\)) available through the network connection to the building \("the last mile"\) to support all concurrent internet users at a school concurrently, how does it get to the students who are spread out in different places in the building?

In technical language this problem is solved by distributing bandwidth either by wires in the building or through the air wirelessly using a technology called "WiFi".

Nowadays in New York City District schools, it's the various administrators' computers in the main office, along with a desktop computer in a classroom for teacher use, that are those connected by wires. The wires are cabling designed for networks that in the jargon are called "CAT 5" or "CAT 6" cables, and are run in the walls. These cables looks like telephone wire (itself technically called "CAT 3") but thicker with slightly bigger, wider jacks. Those of you who use the internet in an office setting 20 years may have had short 3' or 5' versions of these, often simply referred to as a "network cable" that they carried with them to use to connect to the office network.

<img src="/assets/photos/DOE_WAP.jpg" width="250" align="right">The majority of a schools' internet users, especially students, connect wirelessly using WiFi. Using Wifi, bandwidth comes to their device (e.g., a laptop) through a radio signal than emanates from a nearby "Wireless Access Point" (a "WAP"; example from a DOE school pictured to the right). The "WAP" is connected to the "last mile" using the same physical network for CAT 5 or CAT 6 cables that connected devices, like office desktops, that used wired connections.

One of the early problems Wifi helped solve, especially in schools that  that it allowed

In older schools especially, WiFi is an important

### How do these pieces - the public internet and the DOE connection to it, the DOE ring and nodes that compose its WAN, the last mile, and schools' own 


### New York City has never really figured out how to do it right
In 2007 New York City began installing cables, connections and other things required to provide high speed internet to school buildings.  It spent a lot of money, \(over $300 million\) and by one account it did not put adequate controls and oversight in place to ensure that the system-wide upgrade was done properly or within budget.  Surveys done by various people show there are serious limitations on the availability of high speed internet in schools, particularly in areas of underserved students.

In June 2017 New York City asked that companies bid on the right to upgrade the system and has $750 million allocated in a master plan to do so by 2020.  Experts point out that there are serious questions about how the money will be spent and whether by the time the planned upgrades are done they will be adequate.  An [city audit report from 2017](https://comptroller.nyc.gov/wp-content/uploads/documents/SI16_082A.pdf) reports that

### So what is the problem in any one school building?

This is the multi-facetted, complicated question.  The answer is maybe problem 2 \(it does not get the last mile\), problem 3, \(it does not get into the building with enough power for all the students\), problem 4 \(it does not get to where the students need it with enough power for all the students in the class\) OR A COMBINATION OF ALL OF THESE PROBLEMS.
