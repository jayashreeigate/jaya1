#Success
Blueprint has been successfully imported in your local vFabric Application Director. 

There are  few final steps you need to follow before perform this deployment.

###Prerequisites:

Download the "xplanner-plus.war" and "job.sh" files form following links and keep in your local webserver folder.

http://xplanner-plus.sourceforge.net/


###Deployment steps:
1.Now click on deploy to deploy the application.

2.Enter name for deployment profile.

Step1: Deployment Environment tab will be displayed. Enter proper values as per your environment and click next.


Step2: Application Properties -> Service tab

		i. :Preinstalled _MySQL_server_for_OS:
	
			a. db_root_password: Enter the password

![alt tag](https://raw.github.com/vmware-applicationdirector/solutions-import-beta/appd-Clustere-Apache-Hadoop-50-blueprint/AfterDeployment-Step1.jpg)

		
		ii. vFabric_tc_Server_SYSTEM:
	
			a. jobsh: Local webserver path where you kept "job.sh" file 
		
			b. nfs_path: Path of nfs server
		
			c. war: Local webserver path where you kept "HadoopDemoApp.war" file
Step3: Application Properties -> Service tab
	
		i. xplanner_db: xplanner_db_pass
	
![alt tag](https://raw.github.com/vmware-applicationdirector/solutions-import-beta/appd-Clustere-Apache-Hadoop-50-blueprint/AfterDeployment-Step2.jpg)
	
##Blueprint Canvas diagram for your reference: 

![alt tag](https://raw.github.com/vmware-applicationdirector/solutions-import-beta/appd-Clustere-Apache-Hadoop-50-blueprint/Hadoop-Canvas-Diagram.png)

##Ready to go for deployment







 








