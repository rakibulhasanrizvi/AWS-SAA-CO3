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

**Virtual Private Cloud (VPC)**

    Virtual Private Cloud (VPC) = a private virtual network in AWS where we can launch our resources.
    Basically VPC is our own network in cloud which is isolated from other AWS users.
    This virtual network is like the same network of our traditional data center, with the benefits of scalable infrastructure of AWS.
![Amazon VPC](images/VPC.png)

**Subnets**  

    A subnet is a range of IP addresses in your VPC. A subnet must exist in a single Availability Zone. After we add subnets, we can
    deploy AWS resources in our VPC. We can assign both IPv4 and IPv6 addresses, to our VPCs and subnets.

**Route Table**  

    A route table serves as the traffic controller for our VPC. Each route table contains a set of routes, that determine where network
    traffic from our subnet or gateway is directed. Each route specifies a destination and a target. We must add our desired subnets
    (public subnets, private subnets) in the route table via subnet association to define how traffic flows for those subnets.
    
    Here,
    Destination = The range of IP addresses where we want traffic to go.
    Target = The gateway, network interface, or connection through which traffic will be sent to its destination.


