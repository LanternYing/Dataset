﻿----------------------------------------------------------------------------
README file for dataset description
----------------------------------------------------------------------------

This is a archive of the public datasets for QoS prediction. Currently, this 
data folder provides two datasets:

============================================================================
dataset#1: 339 * 5825 Web service QoS dataset
============================================================================

This dataset describes real-world QoS evaluation results from 339 users on 
5,825 Web services. Note that we have recently updated the location 
information (e.g., IP, AS, Latitude, Longitude) of users and services into 
the dataset. It is available for downloading at: 
http://wsdream.github.io/dataset/wsrec_dataset1

----------------------------------------------------------------------------
List of contents of the dataset
----------------------------------------------------------------------------

userlist.txt  - information of 339 service users. Format: | User ID |  
                IP Address | Country | Continent | AS | Latitude | Longitude |
                Region | City |
wslist.txt    - information of the 5,825 Web services. Format: | Service ID |  
                WSDL Address | Service Provider | IP Address | Country | 
                Continent | AS | Latitude | Longitude | Region | City |
rtMatrix.txt  - 339 * 5825 user-item matrix of response-time. 
tpMatrix.txt  - 339 * 5825 user-item matrix for throughput.
readme.txt    - descriptions of the dataset

----------------------------------------------------------------------------
Reference paper
----------------------------------------------------------------------------

This detailed description of this data set can be refereed to this paper:

- Zibin Zheng, Yilei Zhang, and Michael R. Lyu, “Investigating QoS of Real-World 
  Web Services”, IEEE Transactions on Services Computing , vol.7, no.1, pp.32-39, 
  2014.

IF YOU USE THIS DATASET IN PUBLISHED RESEARCH, PLEASE CITE THE ABOVE PAPER. 
THANKS!

----------------------------------------------------------------------------
Acknowledgements
----------------------------------------------------------------------------

We would like to thank PlanetLab (http://www.planet-lab.org/) for collecting 
the dataset, and IPLocation (http://www.iplocation.net/) for collecting the 
location information. We also thank Prof. Mingdong Tang (HNUST) for 
contributing the AS information of the users and services.  


============================================================================
dataset#2: 142 * 4500 * 64 time-aware Web service QoS dataset
============================================================================

This dataset describes real-world QoS evaluation results from 142 users on 
4,500 Web services over 64 different time slices (at 15-minute interval). 
The dataset is available for downloading at: 
http://wsdream.github.io/dataset/wsrec_dataset2

----------------------------------------------------------------------------
List of contents of the dataset
----------------------------------------------------------------------------

rtdata.txt  - response-time values of 4,500 Web services when invoked by 142 
              service users over 64 time slices. Data format:
              User ID | Service ID | Time Slice ID | Response Time (sec)
              e.g.: 98    4352    33    0.311
tpdata.txt  - throughput values of 4,500 Web services when invoked by 142 
              service users in 64 time slices. Data format:
              User ID | Service ID | Time Slice ID | Throughput (kbps)
              e.g.: 91    1196    62    32.88
readme.txt  - descriptions of the dataset

----------------------------------------------------------------------------
Reference paper
----------------------------------------------------------------------------

This detailed description of this data set can be refereed to this paper:

- Yilei Zhang, Zibin Zheng, and Michael R. Lyu, "WSPred: A Time-Aware 
  Personalized QoS Prediction Framework for Web Services", in Proceedings of 
  the 22th IEEE Symposium on Software Reliability Engineering (ISSRE 2011).

IF YOU USE THIS DATASET IN PUBLISHED RESEARCH, PLEASE CITE THE ABOVE PAPER. 
THANKS!

----------------------------------------------------------------------------
Copyright
----------------------------------------------------------------------------

Our datasets are freely available for research purposes. Downloading and 
using the dataset will indicate your acceptance to enter into a GNU General 
Public License agreement. Redistribution of this dataset to any other third 
party or over the Web is not permitted.


