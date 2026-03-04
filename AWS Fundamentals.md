**Availability Zones (AZ)**  

    Availability Zone = AWS Data Center
    Each AZ is physically separated but are connected via high speed, low latency private links within the region.
    So we can think of it as "private connectivity inside the region".
    There are 123 Availability Zones (AZs).
![Availability Zones](images/AZ.png)

**Regions**  

        Region is a geographical area that contains multiple Availability Zones (AZs).
        Each Region contains 2 or more Availability Zones (usually at least 3).
        AWS has 39 Regions globally till now.
![Region](images/Region.png)

**What is Amazon VPC?**

        VPC (Virtual Private Cloud) = a private virtual network in AWS where we can launch our resources.
        Basically VPC is our own network in cloud which is isolated from other AWS users.
        This virtual network is like the same network of our traditional data center, with the benefits of scalable infrastructure of AWS.
![Amazon VPC](images/VPC.png)        
