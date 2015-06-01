## Google Cloud Platform Services - Highlevel

There were times when companies/people order physical servers, manage their resources by contacting a provider.
Managing such as resetting and setting up physical servers etal. .
It is highly unimagenable to perform these operations now mainly because of the time to setup, cost to buy these servers.
And in 5 years from now this will look more insane! That takes me to explain what Google is doing on Cloud.


####GoogleCloudPlatform solves the concern of managing physical servers, databases and software.

GCP provides 4 categories of services that enables developers for an efficient application development.  
1. Infrastructure: Google Compute Engine(GCE)   
This will help in abstracting the physical machines and provides a virtual machine to the user. Now the user need not be concerned about buying infrastructure of the machine such as setting up the Hardware, Operating System. This is also known as Infrastructure as a Service(IaaS). We need not buy anything for the hardware but we need to pay based on our usage - Pay as you go!  
2. Containers: Google Container Engine(GKE)  
The containers layer is an abstraction on the top of Infrastructure(virtual machines). The operations(ops) of the provided virtual machines in the Infrastructure layer are taken care by the containers. Containers take care of running software without being concerned of the underlying hardware. Containers are deployed in the virtual machines. GKE enables developers to deploy their code on a cluster of machines using an open source project - Kubernetes.  
3. Platform: Google App Engine(GAE)  
The platform layer is again an abstraction but on top of Containers. Using Google App Engine- the memory, the number of instances (CPU), the OS upgrades are not needed to be taken care of. When the developer provides backend code of their application, GAE will compile, deploy and scale the application thus making the developers more productive. This is also called as Platform as a Service(PaaS)  

All the above 3 categories offered by GCP are for the server side backend developers.

4. The client side developer of a web application or a mobile developer are also now assisted by GCP using Firebase. Firebase is the platform to develop mobile and web applications. Choosing on how to implement backend of the application is important while developing mobile/web apps. User Authentication, Realtime databases, static hosting are some of the features provided by Firebase. Firebase has integrations with client SDKs such as Android, iOS, JS & Webframeworks such as EmberJS, AngularJS, React, Knockout along with server side access with PHP, Python, Ruby, NodeJS, Golang, Java, Perl.

5. Database: Google Cloud Platform(GCP) -
Using Google cloud storage, developers can avoid the overhead of setting up database on their physical machines. Databases are now created on cloud making them to be easily accessible from anywhere. Google cloud storage is fast and secure, it imeplements a cost effective object storage service and global edge-caching that makes a powerful yet simple cloud storage for the developers. Like other Google cloud services, developers pay as they use. This is also known as Database as a Service(DaaS). Google cloud storage provides a free trial for usage of $300 for the first 6 months.
