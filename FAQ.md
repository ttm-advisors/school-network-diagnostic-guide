## Frequently Asked Questions

* [What is "bandwidth"?](#what-is-"bandwidth"?)
* [Where does bandwidth for schools come from and is there enough to go around?](#where-does-bandwidth-for-schools-come-from-and-is-there-enough-to-go-around?)
* [How does it get to a school building?](#how-does-bandwidth-get-to-a-school-building)
* [Why are wired connections used to connect schools?](#why are wired connections used to connect schools?)

### What is "bandwidth"?
Bandwidth is a measure of internet speed -- the amount of information or data (specifically bits -- the 1s and 0s) that can come to a computer from the internet \(download speed\) and from a computer back to the internet \(upload speed\).

Internet speed is calculated based on how many bits a connection can carry per second. "Bits" are the individual 1s and 0s are most fundamental unit of all digital communication.

Mbps stands for megabits per second and is a common unit used to measure the speed of internet connections. 1 Mbps is equal to 1,000,000 bit per second. Slow network connections may be measured in Kbps (Kbps) - 1,000 bits per second. Very high speed connections will be measured gigabits per second - 1 billion bits per second.

Conversions and examples:
* 1 Gbps = 1000 Mbps = 1,000,000 Kbps = 1,000,000,000 bps.
* Dial-up modems used to connect to the internet in the 1990s were usually 14.4kbps or 28.8kbps
* Early "high speed" DSL and cable modem services were in the area of 500kbps to 1Mbps (1000kbps)
* A standard speed offered by Verizon its home internet service is 100 Mbps, approximately 100x faster than the first generation "high speed" internet services of 20 years ago.
* Some companies now offer 1 Gbps home service.

### Where does bandwidth for schools come from and is there enough to go around?

New York City, given its prominent global stature, is generously supplied with bandwidth to the city. Internet bandwidth comes through the physical lines, owned by large global telecoms, that pass under the Hudson and East Rivers. These telecoms in turn sell internet access to homes and businesses. Some telecoms also choose to resell/wholesale bandwidth to smaller internet service providers who work directly with home and business end users.

The internet traffic for devices of the administrators, teachers, and students working and studying in 1,300 buildings that comprise the NYC DOE physical plant is routed, like a funnel, through one gateway to one of these private internet service providers. The DOE recently completed a [bid process](https://a856-cityrecord.nyc.gov/RequestDetail/20170614013) for a new internet service provider to increase total gateway capacity from 24Gpbs to 240Gbps, a 10x increase. Lightower won the contract in late 2017 and is in the process of doing its upgrade.

### How does bandwidth get to a school building?
The problem with internet access to schools really starts with getting enough bandwidth into the school building itself. There are two pieces to how internet traffic gets from from the DOE's internet gateway (Lightower) to a school:

* First internet traffic travels from Lightower's connection to the Internet into large capacity fiber optic wires, leased by the DOE. The lines that create a "ring" across the city that connect seven Department of Education "nodes". A node is a meeting point of network connections, much like the the joints that might connect different water pipes in a plumbing system.

* Second schools are connected to whichever of these seven nodes on the ring is geographically closest to their building. They are connected to the ring via a wired connection, called a circuit, provided by either Verizon or Lightower. The speed  of this connection may range from 10 Mbps to 100 Mbps. This connection from the school building to the closet DOE "node" is sometimes referred to as the "last mile" (and the problem of getting enough bandwidth through that connection the "last mile problem"). The DOE is currently in the process upgrade all circuits in the city to each school building to 100Mpbs for single school campuses, 150 Mbps for shared campuses.

Together - the city ring and its 7 nodes, as well as the  individual circuits used to connect school buildings to the ring, are sometimes referred to as the DOE's "Wide Area Network" ("WAN").

### Why are wired connections - the circuits - used to connect schools?
Given the concentration of buildings and obstructions in New York City coupled with the bandwidth requirements wireless technologies are not yet practical or price appropriate for connecting schools to the DOE within the city, despite the recent evolution in high bandwidth wireless technologies. An exciting development, is mesh networking, which uses low power, short distance wireless connectivity. For the foreseeable future though last mile wired connections will be the norm.


### How much does last-mile bandwidth does the school building need?
If you have only enough water to run your sink but not your sink and your toilet, you don’t have enough water coming into the house. The same holds true for bandwidth to the internet - just as there needs to be enough water pressure for each toilet and shower, there needs to be enough internet - enough bandwidth - to serve everyone who wants to use it in a school building.



How much bandwidth is needed in a school? A common refrain is that all schools need "high speed internet" or "broadband". [Until 2015 the FCC definition on "high speed" was 4Mbps](https://www.nbcnews.com/tech/internet/faster-internet-fcc-sets-new-definition-broadband-speeds-n296276) when the [FCC definition was upgraded to 25Mbps](https://www.fcc.gov/reports-research/guides/broadband-speed-guide).

 The FCC also provides some guidelines for how much bandwidth is required for various common internet uses, including
* "General Browsing and Email - 1 Mbps"
* "File Downloading - 10Mbps"
* "Streaming Standard Definition Video - 3-4 Mbps"

As context before 2007 the NYC DOE used an older technology to provide last mile connections (called "Frame Relay"). In 2007 the DOE started the process of upgrading its last mile connections with newer technology to bring schools to a total bandwidth of (at least) 10 Mbps. This target has since been revised to a target of 100 Mbps per school, 150 Mbps, and schools' last mile connections are in the process of being upgraded.

Back to the question of if that's enough. Based on the FCC guidelines let's assume in a single school the following:
* 10 administrators are using the network for email and general browing (10 x 1Mbps = 10 Mbps)
* 30 students are downloading files for a science project (10 x 30 = 300 Mbps)
* 20 students in a lab are viewing a streaming video portion of an online literacy program (20 x 4 = 80 Mbps)
The total required bandwidth for this very modest usage scenario is 390 Mbps, nearly 4x to the target for individual school bandwidth.

What are the implications of the aggregate bandwidth exceeding what's available? While the administrators will probably not notice much lag as they use email, the students download files will spend more time waiting and less time on task. Some students' file downloads may time out causing them to have to restart downloads. The students watching video lessons experience buffering that distracts for the lessons and results in them taking more time that could be otherwise spent on task. We've each probably experienced something similar when too many people try and use hot water at the same time in a house -- someone ends up with a cold shower.

### How do you get the internet in the school building to the students who want to use it?
Assume the network connection  enough internet to the building \(the last mile\), and you have enough internet coming inside the building \(band with\), but how do you get it to the students who are spread out in different places in the building?    It’s like you have only one sink or shower in your house, or worse yet only one toilet.  If everyone has to “go” at the same time, well you get the idea.  In internet language this problem is solved by  “routing” the internet either by wires in the building or through the air which is called “Wi Fi”.  School buildings which are older \(most\) have old wiring that is likely to be too old to carry enough power, and is unlikely to go where the students now use the internet.  It may go to one classroom only.  It may be so thin and old that it only allows a small amount of internet to go through it.  In the water analogy there may be  leaky pipes in the kitchen and bathroom, so just sending more “band with” into a school or to a classroom may not help.  The internet, like the water in the pipes, is leaking out before it gets to the place the student needs it.  In any event, at some point  it lands somewhere in the building and it is connected by wire or “wi Fi” to a “router”, which often looks like a small saucer on the wall or the ceiling.

### New York City has never really figured out how to do it right
(Note to P.S.: Which specific projects, in 2007 and in 2017, does this refer?)

In 2007 New York City began installing cables, connections and other things required to provide high speed internet to school buildings.  It spent a lot of money, \(over $300 million\) and by one account it did not put adequate controls and oversight in place to ensure that the system-wide upgrade was done properly or within budget.  Surveys done by various people show there are serious limitations on the availability of high speed internet in schools, particularly in areas of underserved students.

In June 2017 New York City asked that companies bid on the right to upgrade the system and has $750 million allocated in a master plan to do so by 2020.  Experts point out that there are serious questions about how the money will be spent and whether by the time the planned upgrades are done they will be adequate.  An [city audit report from 2017](https://comptroller.nyc.gov/wp-content/uploads/documents/SI16_082A.pdf) reports that

### So what is the problem in any one school building?

This is the multi-facetted, really complicated question.  The answer is maybe problem 2 \(it does not get the last mile\), problem 3, \(it does not get into the building with enough power for all the students\), problem 4 \(it does not get to where the students need it with enough power for all the students in the class\) OR A COMBINATION OF ALL OF THESE PROBLEMS.
