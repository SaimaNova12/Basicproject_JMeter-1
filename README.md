### Performance Testing
============================================

#### In the above files performance test is performed on frequently used API for test App. 
#### Test executed for the below mentioned scenario in server 000.000.000.00. 

- ##### 100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 6.667 And Total Concurrent API requested: 400.
- ##### 200 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 7     And Total Concurrent API requested: 800.
- ##### 300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 16    And Total Concurrent API requested: 1200.
- ##### 500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 21    And Total Concurrent API requested: 2000.
#### While executed 600 concurrent request, found 26 request got connection timeout and error rate is 0.23%. 
#### Summary: Server can handle almost concurrent ---- API call with almost zero (0) error rate.
#### Find the details report from the attachment
