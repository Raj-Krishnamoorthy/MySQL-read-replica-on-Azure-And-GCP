
README.MD
This document is only for educational and demo purpose only.

How to create read replica on Azure database for MySQL - Screenshots attached


AND


How to create read replica on GCP for Cloud SQL (MySQL) - Screenshots attached

High level comparison MySQL DB read replica creation on Azure and GCP based on the demo experience. Views expressed here is purely on my personal experience.
 
Prerequisite : Personal subscription used on both Azure and GCP

Azure : Goto Create Resource & type MySQL

![image](https://user-images.githubusercontent.com/49286341/64314893-6682b780-cf65-11e9-9c25-f52186e1d993.png)

Supply required fields

![image](https://user-images.githubusercontent.com/49286341/64314911-713d4c80-cf65-11e9-8e06-ed8497875eb8.png)

Master server gets created

![image](https://user-images.githubusercontent.com/49286341/64314915-78645a80-cf65-11e9-8b13-8b33edea957b.png)

Click on the REPLICATION under Settings on the RIGHT-HAND Menu

![image](https://user-images.githubusercontent.com/49286341/64314921-7dc1a500-cf65-11e9-99d9-4a0160e10bf9.png)



![image](https://user-images.githubusercontent.com/49286341/64314929-82865900-cf65-11e9-8b5a-47208599131d.png)


Read REPLICA gets created

![image](https://user-images.githubusercontent.com/49286341/64314941-86b27680-cf65-11e9-8a81-929ba3e9f999.png)


Once read replica is created use your client to connect using the connection strings present under settings to connect to Azure Database for MySQL



GCP : How TO CREATE READ REPLICA FOR CLOUD SQL

Supply all the required fields

![image](https://user-images.githubusercontent.com/49286341/64314963-9631bf80-cf65-11e9-88a1-942f0ac4680a.png)


Choose the Instance configuration depending upon your requirements


![image](https://user-images.githubusercontent.com/49286341/64314968-9a5ddd00-cf65-11e9-90da-cb424f68d83a.png)


Make sure auto backups and logging enabled

![image](https://user-images.githubusercontent.com/49286341/64314976-9e89fa80-cf65-11e9-8475-7f55576c6b8c.png)


Click Create

![image](https://user-images.githubusercontent.com/49286341/64314979-a21d8180-cf65-11e9-898c-87edd2d88733.png)


Once the master server is created, Click ADD to create the read replica


![image](https://user-images.githubusercontent.com/49286341/64314987-a5b10880-cf65-11e9-919b-48ec8543d73b.png)


Supply the values for required fields


![image](https://user-images.githubusercontent.com/49286341/64314995-a9448f80-cf65-11e9-92ac-f3749feb3d61.png)


Click Create

![image](https://user-images.githubusercontent.com/49286341/64315005-ad70ad00-cf65-11e9-89f2-11d3249caaca.png)



![image](https://user-images.githubusercontent.com/49286341/64315020-b6617e80-cf65-11e9-85cb-311775697adf.png)

READ REPLICA Is ready


![image](https://user-images.githubusercontent.com/49286341/64315047-cb3e1200-cf65-11e9-9d59-a139f51f9b3d.png)





