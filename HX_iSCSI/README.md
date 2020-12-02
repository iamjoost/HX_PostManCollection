## REST APIs for iSCSI on HyperFlex 4.5+ cluster.
HX APIs do need an token to authenticate. The following steps will guide you through a process which will get the HX Token en Cluster UUID, which is needed for the some API calls.

#### STEP1: 
Start with filling in the HX IP address in the Variables HXCIP
![ALT Text](https://i2.wp.com/iamjoost.com/wp-content/uploads/2020/07/Postman-hxcip.png)

#### STEP2. 
Open STEP 2: Get HX Access Token
Fill in the username and password in the body to get an Access Token.
Hit **SEND** and the token will be copied into the Collection variable.
 ![ALT Text](https://i0.wp.com/iamjoost.com/wp-content/uploads/2020/07/HX-Access-Token-Body.png)

#### STEP3 to get the Cluster UUID.
Open STEP3: Get HX Cluster UUID and hit **SEND**.
This Cluster UUID will be copied into the Collection variable **CUUID**.

#####Now you can play with the HX iSCSI collection.  

You can always see the HyperFlex API Explorer on the cluster via : **HTTPS://HX_Cluster_IP_Address/apiexplorer**
  
