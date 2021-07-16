# dfrws2016-challenge
The 2016 DFRWS Forensic Challenge seeks to advance the state-of-the-art in SDN forensics by focusing the community's attention on this emerging domain.

## Scenario
You have obtained a memory image from an SDN switch, along with a capture of the network traffic between the SDN switch and its controller(s), i.e., the "southbound" traffic. Your job is to analyze these artifacts for forensically interesting information. Download the:

Memory image  MD5: 0a3d12a8930793a27a441a45e9a7a6f8

Packet capture  MD5: 2b44c4a8deeffe7927ec3497994222c0

## Challenge
Your job is to develop automated tools for analyzing southbound SDN forensic artifacts. Tools that fuse analysis of network traffic and memory dumps are especially encouraged. We know what hosts were connected to the SDN switch, what they did, and who they communicated with -- as well as the network policy and configuration as implemented by our SDN controller. Your tool should seek to reverse engineer as many of these details as possible! Some suggestions:

* What type of SDN switch and controller are in use?
* What hosts (identified by MAC or IP addresses) were connected to which switch ports?
* How much traffic did these hosts send, and to whom?
* When were these hosts active (they may be virtual hosts in a cloud that move and are short-lived)?
* What flows does the SDN switch match on? Are they static or dynamic rules?
* What actions does the SDN switch take, and for which flow rules?

## Results

Four teams participated in this year's challenge and did excellent work. Congratulations to the winning team from Booz Allen! A summary of the challenge, scenario details, results, and the winning solution are available for download:

Results Presentation (Given at @DFRWS Seattle Aug, 2016)

Winning submission
