# wifi-traffic-dataset

This dataset consists of downlink traffic captures of 7 different multimedia applications: Netflix, Youtube, Youtube Live, Twitch, Spotify, Whatsapp and Skype. Wireshark packet analyzer tool is used for the construction of this dataset.

A.Duration:

Each application has 30 captures which are around 11-12 minutes long.  First 1 minute-period and the period after 11 minutes are silent periods for observing the stabilization. In other words, each capture provides clear 10 minutes-long downlink traffic between 60-660 seconds.   

B.Features:

1)"No": Packet number

2)"Time" (seconds): Time stamp of the packet which refers to the time passed since the beginning of capturing until the packet was captured.

3)"Source": MAC layer name of the traffic source.

4)"Destination":  MAC layer name of the traffic destination.

5)"Protocol": Communication protocol that is used for the traffic.

6)"Type/Subtype": Content type of the packet. We filtered the traffic to get QoS Data only.

7)"Length" (bytes): Size of the packet in bytes.

8)"Time delta from previous displayed frame" (seconds): Inter-arrival time between the current packet and the previous displayed packet in the dataset. 

9)"Info": provides following information about the packet: data type, sequence number(SN), fragment number(FN) and flags

10)"Time shift for this packet": Time shift was not used in this dataset.

 
