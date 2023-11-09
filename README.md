# credo_files
data files from CREDO project

image_4class.zip  : artefats (1123), worms(305), lines (tracks) 394 , dots 536

                    manual classification by voting method

all_set.zip (9.3Mb)  all_set.shape=(121286, 60, 60, 1):

  numpy array of images , after two filters:
  
     1. threshold image.mean()/image.max()<0.003
     
     2. horizontal alignment using Tomek Hachaj's algorithm 




https://github.com/credo-ml/basic_detect.git :

Detections from 01.10.2022 (from 00:00 PL time) to 01.10.2023 - passed only after frequency filtering (10 per minute on 1 device) and anti-artifact filtering       (brightness condition min.1 max. 70 with a brightness of 70 on the grey scale). The collection contains only traces from Android devices (IOS devices and         traces from the Advacam detector have been omitted).

The weight of the packed *.png traces separated into 69 small packets from a time range of 1 year weighs in at approx. 1.2 GB Json files from these detections       weigh in at approx. 3 GB - to be obtained by email contact (contact[at]credo.science)
