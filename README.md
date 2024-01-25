### Performance Testing
============================================

#### In the above files performance test is performed on frequently used API for test App. 
#### Test executed for the below mentioned scenario in server 000.000.000.00. 

- ##### 100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 6.667 And Total Concurrent API requested: 400.
- ##### 200 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 7     And Total Concurrent API requested: 800.
- ##### 300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 16    And Total Concurrent API requested: 1200.
- ##### 500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 21    And Total Concurrent API requested: 2000.
- ##### 600 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 28    And Total Concurrent API requested: 2400.
#### While executed 600 concurrent request, found 26 request got connection timeout and error rate is 0.75%. 
#### Summary: Server can handle almost concurrent 2250 API call with almost zero (0) error rate.
#### Find the details report from the attachment
![WhatsApp Image 2024-01-25 at 3 21 06 PM](https://github.com/SaimaNova12/Project_JMeter-1/assets/76209488/74235248-97e2-480a-a060-2b494aa9a5bb)
![WhatsApp Image 2024-01-25 at 3 16 52 PM](https://github.com/SaimaNova12/Project_JMeter-1/assets/76209488/5ae7e186-0c24-433a-a66a-6188e22c5b93)
