How to extract data for reporting in jmeter
============================================
Dear OpenCart, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in 
1.(HOME Page) https://www.opencart.com/index.php?route=common/home  =>
	(FEATURE Page) https://www.opencart.com/index.php?route=cms/feature  =>
		(MARKECTPLACE Page) https://www.opencart.com/index.php?route=marketplace/extension  =>
			(ABOUT US Page)	https://www.opencart.com/index.php?route=cms/company  =>
				(LOGIN Page)  https://www.opencart.com/index.php?route=account/login 

1 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 3.350 And Total Concurrent API requested: 212 Error Rate 0%.
2 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 7 And Total Concurrent API requested: 424 Error Rate 0%.
3 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 11 And Total Concurrent API requested: 636 Error Rate 0.47%.
4 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 14.1 And Total Concurrent API requested: 848 Error Rate 0.59%.
5 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 17.6 And Total Concurrent API requested: 1060 Error Rate 0.94%.
6 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 20 And Total Concurrent API requested: 1272 Error Rate 1.18%.


While executed 3 concurrent request, found  636 request got connection timeout and error rate is 0.47%. 

Summary: Server can handle almost concurrent 424 API call with almost zero (0) error rate.

 
