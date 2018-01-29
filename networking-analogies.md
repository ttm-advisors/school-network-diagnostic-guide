# Conceptualizing Networks: The Water Analogy
Perhaps the most common metaphor used to describe computer networks is that of our **water** system. Many computer networking terms, "pipe" being perhaps the best example, come from the water system.

Just as our water comes originally from a reservoir, lake, or well - perhaps one quite distant, so too does the data on our devices' screens start on a remote server that might be located nearly anywhere on the planet. Water embarks on its journey to your bathtub in enormous pipelines \(aqueducts\). Similarly data departs a server to traverse first the massive trunk lines, owned by global telecoms, which compose the core of the public internet (i.e., the "internet backbone").

As water flows closer to consumers and businesses, it is routed into the smaller pipes owned by municipal water companies that distribute water to buildings. Similarly data passes from the public internet backbone to pipes that get smaller as they get closer to the end user.

Finally water enters a building where it flows through plumbing to various floors and ultimately to bathrooms, laundry rooms, kitchens, etc. for end use. Data from the internet similarly enters a building (via a router or modem) after which it travels through a local wired or wireless network (the LAN) to the end user.

Compare:

| Water                          | Data (on a computer network)                     |
|--------------------------------|--------------------------------------|
| Starts in a well, lake,  or reservoir (where it was collected from rain and nearby natural sources such as springs, streams, etc.)| Starts on a remote server (to where it was uploaded by a programmer, author, creator, data scientists, another computer, etc.)|
| Flows first through large pipelines as it travels to to cities and towns | Flows from server facilities first across trunk lines that compose the internet backbone
| Is routed across a region or state into various smaller pipes that channel water to specific municipal water districts | Is routed across gradually smaller lines (size being measured by how much data each line can handle at any one time)
| Water enters the smaller system of pipes that compose a municipal water system (i.e., the plants and pumping station as well as the pipes that run under the street and into buildings) | Data enters the network of an Internet Service Provider, where it then transverses a set lines, usually copper or fibre, also usually underground that are geographically connected from a central connection to the internet backbone to points nearby individual homes, businesses. |
| Water travels through a water service pipe its final few yards from the municipal water main. It then passes through a meter, and then into the buildings' plumbing. Responsibility for both the water and the plumbing now resides with the building owners and tenants | Data travels its "last mile" over a twisted pair, copper, coax, fibre, some hybrid, or something similar. Alternatively in the case of a wireless device using cellular service, the "last mile" is the wireless signal from the local cell tower to these device. |
| Water is routed with the home to sinks, toilets, baths, etc. | Data comes in via a router or modem and is then routed within an internal business, school, or home network, likely using wireless (wifi) technology to connect individual devices to the network, though servers and desktops may use a wired connection to connect the local network. |

Ownership, control, and responsibility for the network are useful points of comparison as well as they illuminate governance and accountability considerations.

| Water | Home Networks | Business Networks | School Networks |
|-------|---------------|-------------------|------------------|
| The large pipes that carry high volumes of water within and between states are controlled and managed by large public or quasi-public agencies that manage distribution | The large trunk lines that form the internet backbone are | (Same) | (Same)
| Municipal water companies control distribution in a geography and own (or control) a network a piping within a geography | An ISP like Verizon, Spectrum, etc. | An ISP that serves business customers, generally providing higher levels of reliability | The DOE's own private WAN that is composed of leased lines, circuits, and a SONET ring |
| Internal plumbing owned by the building own and maintained by building owners / and/or tentants | The internal hardware used for a home network; the modem may be owned by the ISP but any additional hardware (e.g., a wireless access point) is bought and managed by the home owner. | Internal hardware owned and managed by a business; ownership and/or management may be outsourced to a 3rd party provider | Network equipment owned and managed by the DOE in individual schools buildings
