##REST APIs for Datastore management on HyperFlex 4.0+ cluster.
HX APIs do need an token to authenticate. The following steps will guide you through a process which will get the HX Token en Cluster UUID, which is needed for the Datastores.

####STEP1: 
Start with filling in the HX IP address in the Variables HXCIP
[ALT Text](https://i2.wp.com/iamjoost.com/wp-content/uploads/2020/07/Postman-hxcip.png)

####STEP2. 
Fill in the username and password to get an Access Token.
Hit SEND and the token will be copied into the Collection variable.

####STEP3 to get the Cluster UUID.
This Cluster UUID will be copied into the Collection variable.

Now you can play with the Datastore collection.  
You can use the order of the DS numbering and this is not a requirement.

When you create a Datastore, the Datastore UUID is saved in the variable **dsuuid**.  
The Edit Datastore and Delete datastore are using these variables.

You can always see the HyperFlex API Explorer on the cluster via : **HTTPS://<HX Cluster IP Address>/apiexplorer**
  
