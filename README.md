# capstoneProject2-RA: Analyzing TransJakarta Route in April 2023
# Background

TransJakarta are the first Bus Rapid Transit (BRT) in Southeast Asian and started to operate since 01 Februari 2004. After 20 years operating, TransJakarta consist of 252 stops distributed across 14 main corridors. TransJakarta are divided into three types of fleets: Regulars TransJakarta, RoyalTrans, and JakLingko.

TransJakarta, which continuously evolves, is also accompanied by the growth of its user base over time. The increasing number of fleets, services, and facilities reflects TransJakarta's concern for public transportation users. As an effort to provide the best services and facilities to its users, an analysis is needed to understand the behavior of transportation users provided by TransJakarta.
# Problem and Goals
With the aim of developing TransJakarta transportation sustainably, the main issue to be addressed in this data is to **Analyze the Travel Pattern of Transjakarta Users to Understand the Optimalization of TransJakarta Services in Jabodetabek?**

The purpose of delving into this issue is to identify the travel patterns of TransJakarta users so that TransJakarta can create targeted services and facilities.

# Brief Summary of the Dataset of TransJakarta
1.	transID: Unique transaction id for every transaction
2.	payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
3.	payCardBank: Customers card bank issuer name
4.	payCardName: Customers name that is embedded in the card.
5.	payCardSex: Customers sex that is embedded in the card
6.	payCardBirthDate: Customers birth year
7.	corridorID: Corridor ID / Route ID as key for route grouping.
8.	corridorName: Corridor Name / Route Name contains Start and Finish for each route.
9.	direction: 0 for Go, 1 for Back. Direction of the route.
10.	tapInStops: Tap In (entrance) Stops ID for identifying stops name
11.	tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
12.	tapInStopsLat: Latitude of Tap In Stops
13.	tapInStopsLon: Longitude of Tap In Stops
14.	stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
15.	tapInTime: Time of tap in. Date and time
16.	tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
17.	tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
18.	tapOutStopsLat: Latitude of Tap Out Stops
19.	tapOutStopsLon: Longitude of Tap Out Stops
20.	stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
21.	tapOutTime: Time of tap out. Date and time
22.	payAmount: The number of what customers pay. Some are free. Some not.

