Perhaps the most common metaphor used to describe computer networks is that of our **water** system. Many computer networking terms, "pipe" being perhaps the best example, come from the water system.

Just as our water comes originally from a reservoir, lake, or well - perhaps one quite distant, so too does the data on our devices' screens start on a remote server that might be located nearly anywhere on the planet. Water embarks on its journey to your bathtub in enormous pipelines \(aqueducts\). Similarly data departs a server to traverse first the massive trunk lines, owned by global telecoms, and which compose the core of the public internet (the "internet backbone").

As water flows closer to consumers, it then enters the smaller pipes owned by municipal water companies that distribute water to buildings. Similarly data passes from the public internet backbone to pipes that get smaller as they get closer to the end user.

Finally water enters a building where it flows through plumbing to various floors and ultimately to bathrooms, laundry rooms, kitchens, etc. for end use. Data from the internet similarly enters a building or how via a router or modem after which it travels through a local wired or wireless network to the end user.

Compare:

| Water                          | Data (on a computer network)                     |
|--------------------------------|--------------------------------------|
| Starts in a well, lake,  or reservoir (where it was collected from rain and nearby natural sources such as springs, streams, etc.)| Starts on a remote server (to where it was uploaded by a programmer, author, creator, data scientists, another computer, etc.)|
| Flows first through large pipelines as it travels to to cities and towns | Flows from server facilities first across trunk lines that compose the internet backbone
| Is routed across a region or state into various smaller pipes that channel water to specific municipal water districts | Is routed across gradually smaller lines (size being measured by how much data each line can handle at any one time)
| Water enters the smaller system of pipes that compose a municipal water system (e.g., the pipes that run under the street and into buildings) | Data enters the network of an Internet Service Providers, where it transverses a set lines that are geographically connected from a central connection to the internet backbone to points nearby individual homes, businesses. |
| Water enters passes into a building water main and enters the buildings' plumbing | Data travels its "last mile" either over a line such as DSL or cable (or alternatively in the case of, say, wireless device using cellular service, from the local cellular tower wirelessly to the device) |
| Water is routed with the home to sinks, toilets, baths, etc. | Data comes in via a router or modem and is then routed within an internal business, school, or home network, likely using wireless (wifi) technology to connect individual devices to the network, though servers and desktops may use a wired connection to connect the local network. |

Ownership, control, and responsibility for the network are useful points of comparison as well as they illuminate governance and accountability considerations topics relevant

| Water | Home Networks | Business Networks | School Networks |
|-------|---------------|-------------------|------------------|
| The large pipes that carry high volumes of water within and between states are controlled and managed by large public or quasi-public agencies that manage distribution | The large trunk lines that form the internet backbone are | (Same as Home) | (Same as Home)
| Municipal water companies control distribution in geography and own (or control) a network a piping within a geography |
















 he first step in that journey is . Along the way the water, as is the case for New York City, often is stored temporarily in a smaller holding reservoir. In the case of New York City water is stored along the way to the city in the Kensico and Hillview reservoirs.

The reservoirs bring to mind the idea in computer networks of a \(cache\). Caching - nearby storage of a piece of data whose master version is further away from where its used - is critical to modern day computer networking, and computing more generally.


It has to come from somewhere before it gets to our homes. Potable water usually originates at a , or perhaps from a well that taps into the underground water table \(for a moment we'll set aside rain and how the water got there in the first place, though it does provide some useful context later on when we get to the concept of caching\).

For let's think of the resources on the internet -- all the websites, servers, data, etc. as reservoirs and lakes from which you'll draw, like water, data from \(that you need to send data back, unlike water supply, we'll deal with in a bit\).

From there a reservoir or lake water then starts to flow towards our homes.


Going back to our water example, caching services like CloudFlare, act as local reservoirs. They distribute stores of the most recent version of popular web sites around the world. When you connect to a popular web site most likely what your device has really connected to is a geographically local store's copy of the website.

Continuing further still with the overall idea of networks as we do water, the overall idea of these aqueducts and reservoir can be thought of as the internet generally and that the final aqueduct into your water system as your ISP. And no matter how big pipes are in places, the fastest water will flow is speed through which it can flow through the most narrow pipe and this usually the ISP, the last mile for networks.

For purposes of understanding networks, especially networks like those

Of course, there is no pipe directly the aqueducts and pipelines to your home, office, or in this case, school.

which hold the most recent versions of popular web site in caches geographically scatter around the world, serve in a similar way to the Kensico and Hillview reservoirs do for NYC.





--------

PS Original

-------



Problem  Number 1: Where does it come from?

The internet comes from somewhere, and never mind where because that is not the problem in New York City.  New York City has lots of internet to go around.

Problem Number 2:  How does it get to a school building?

The problem with access for schools starts with getting enough of it into the school building.  It has to come from a wire \(forget about satellites and things that don’t require wires – NYC has too many buildings and obstructions to make transmission other than by wires possible for these purposes\).  It has to come from some central place in NYC \(like a lake or well for water\) to the school building  Let’s call this the “last mile problem”.

Problem Number 3:  How much does the school  building need?

If you have only enough water to run your sink but not your sink and your toilet, you don’t have enough water coming into the house  The same with the internet.  It has to come that last mile with enough “vroom” \(like water pressure\) to serve everyone who wants to use it in a school building.  They call this “band with”, which is the amount of information or data that can come to a computer from the internet \(download speed\) and from a computer back to the internet \(upload speed\).  How much band with is needed in a school?  Way back when the Government said a student needed 10 of something; now it says a student needs 100 of the same thing; but everyone knows that the answer is it depends.  In the water example, if everyone in your house is taking a shower, there isn’t likely to be enough water to go around.  Or to use a more graphic example, suppose that the internet is like a big sewer.  If everyone in a house flushes the toilet at the same time the sewer might fill up to fast and overflow, causing back ups.

Problem Number 4:  How do you get the internet in the school building to the students who want to use it?

Assume you have enough internet to the building \(the last mile\), and you have enough internet coming inside the building \(band with\), but how do you get it to the students who are spread out in different places in the building?    It’s like you have only one sink or shower in your house, or worse yet only one toilet.  If everyone has to “go” at the same time, well you get the idea.  In internet language this problem is solved by  “routing” the internet either by wires in the building or through the air which is called “Wi Fi”.  School buildings which are older \(most\) have old wiring that is likely to be too old to carry enough power, and is unlikely to go where the students now use the internet.  It may go to one classroom only.  It may be so thin and old that it only allows a small amount of internet to go through it.  In the water analogy there may be  leaky pipes in the kitchen and bathroom, so just sending more “band with” into a school or to a classroom may not help.  The internet, like the water in the pipes, is leaking out before it gets to the place the student needs it.  In any event, at some point  it lands somewhere in the building and it is connected by wire or “wi Fi” to a “router”, which often looks like a small saucer on the wall or the ceiling.

Problem 5:  New York City has never really figured out how to do it right

In 2007 New York City began installing cables, connections and other things required to provide high speed internet to school buildings.  It spent a lot of money, \(over $300 million\) and by one account it did not put adequate controls and oversight in place to ensure that the system-wide upgrade was done properly or within budget.  Surveys done by various people show there are serious limitations on the availability of high speed internet in schools, particularly in areas of underserved students.    In June, 2017 New York  City asked  that companies bid on the right to upgrade the system and has $750 million allocated in a master plan to do so by 2020.  Experts point out that there are serious questions about how the money will be spent and whether by the time the planned upgrades are done they will be adequate.

So what is the problem in any one school building?

Now your asking a really complicated question.  The answer is maybe problem 2 \(it does not get the last mile\), problem 3, \(it does not get into the building with enough power for all the students\), problem 4 \(it does not get to where the students need it with enough power for all the students in the class\) OR A COMBINATION OF ALL OF THESE PROBLEMS.


\(for a moment we'll set aside how the water got there in the first place - we'll to that in a bit when we introduce the concept of caching\).


 .  over which internet traffic   itself connected via a very large pipe to the public internet, which itself is built up of massive pipes that form the "internet backbone" itself.
