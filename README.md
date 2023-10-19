# Classification of Network Traffic based  NetTiSA flow

The novel extended IP flow called NetTiSA (Network Time Series Analysed) flow contains a universal bandwidth-constrained feature vector consisting of 20 features. We divide the NetTiSA flow classification features into three groups by computation. The first group of features is based on classical bidirectional flow information---a number of transferred bytes, and packets.  The second group contains statistical and time-based features calculated using the time-series analysis of the packet sequences. The third type of features can be computed from the previous groups (i.e., on the flow collector) and improve the classification performance without any impact on the telemetry bandwidth.

The NetTiSA flow is implemented into IP flow exporter ipfixprobe: https://github.com/CESNET/ipfixprobe

Codes were created for the paper: 


    NetTiSA: Extended IP Flow with Time-series Features for Universal Bandwidth-constrained High-speed Network Traffic Classification -- Josef Koumar, Karel Hynek, Jaroslav Pešek, Tomáš Čejka -- which was submitted to The International Journal of Computer and Telecommunications Networking. 
    
Preprint is available on ArXiv: [PDF](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjTr9bo0IKCAxXq9bsIHcYPAy0QFnoECBwQAQ&url=https%3A%2F%2Farxiv.org%2Fpdf%2F2307.13434&usg=AOvVaw3w_7QtAVYFdgmHl3DGtYfh&opi=89978449) [RESEARCHGATE](https://www.researchgate.net/publication/374556767_NetTiSA_Extended_IP_Flow_with_Time-series_Features_for_Universal_Bandwidth-constrained_High-speed_Network_Traffic_Classification)

Datasets were published in Zenodo repository https://zenodo.org/record/8301043




    Josef Koumar, Karel Hynek, Jaroslav Pešek, & Tomáš Čejka. (2023). Network traffic datasets with novel extended IP flow called NetTiSA flow [Data set]. Zenodo. https://doi.org/10.5281/zenodo.8301043
    

Copyright © 2023, Czech Technical University in Prague, CESNET a.l.e., Josef Koumar (koumajos@fit.cvut.cz), Karel Hynek (hynekkar@cesnet.cz), Tomáš Čejka (cejkat@cesnet.cz)
