### Performance Testing
============================================

#### In the above files performance test is performed on frequently used API for test App. 
#### Test executed for the below mentioned scenario in server 000.000.000.00. 

- ##### 100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 6.667 And Total Concurrent API requested: 400.
- ##### 150 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 10    And Total Concurrent API requested: 600.
- ##### 160 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 11    And Total Concurrent API requested: 640.
- ##### 180 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 14   And Total Concurrent API requested: 760.
#### While executed 180 concurrent request, found 17 request got connection timeout and error rate is 0.23%. 
#### Summary: Server can handle almost concurrent 700 API call with almost zero (0) error rate.
#### Find the details report from the attachment
