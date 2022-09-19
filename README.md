# AliExpress_LoadTesting_Jmeter

HTTP Methode:
POST Method: Create new Account
GET Method: Get Customer with id
POST Methode: Authentication for token
PUT Methode: Update booking info
DELETE Methode: Delete Customer info

Dear viewers, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 

1000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 120 And Total Concurrent API requested: 8500.

2000 Concurrent Request with 2 Loop Count; Avg TPS for Total Samples is ~ 90 And Total Concurrent API requested: 9400.

3000 Concurrent Request with 2 Loop Count; Avg TPS for Total Samples is ~ 85 And Total Concurrent API requested: 8500.

4000 current Request with 1 Loop Count; Avg TPS for Total Samples is ~ 77And Total Concurrent API requested: 7000.

5000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 70And Total Concurrent API requested: 6800

While executed 5000 concurrent request, found  82request got connection timeout and error rate is 1.7%. 

Summary: Server can handle almost concurrent 8500API call with almost zero (0) error rate.

Please find the details report from the attachment and  let me know if you have any further queries. 
