![Alt text] (/Host_a_Static_Website_on_AWS.png)

Host a static Website on AWS
I recently finished a DevOps project where I hosted a sta􀆟c html web app on AWS, u􀆟lizing the resources listed below. 
I have uploaded the reference diagram and scripts I used to deploy the web app on an EC2 instance to a GitHub repository for the project. Please use this informa􀆟on to create a readme file for the project.

1. Configured a Virtual Private Cloud (VPC) with both public and private subnets across two different availability zones.
2. Deployed an Internet Gateway to facilitate connec􀆟vity between VPC instances and the wider Internet.
3. Established Security Groups as a network firewall mechanism.
4. Leveraged two Availability Zones to enhance system reliability and fault tolerance.
5. U􀆟lized Public Subnets for infrastructure components like the NAT Gateway and Applica􀆟on Load Balancer.
6. Implemented EC2 Instance Connect Endpoint for secure connec􀆟ons to assets within both public and private subnets.
7. Posi􀆟oned web servers (EC2 instances) within Private Subnets for enhanced security.
8. Enabled instances in both the private Applica􀆟on and Data subnets to access the Internet via the NAT Gateway.
9. Hosted the website on EC2 Instances.
10. Employed an Applica􀆟on Load Balancer and a target group for evenly distribu􀆟ng web traffic to an Auto Scaling Group of EC2 instances across mul􀆟ple Availability Zones.
11. U􀆟lized an Auto Scaling Group to automa􀆟cally manage EC2 instances, ensuring website availability, scalability, fault tolerance, and elas􀆟city.
12. Stored web files on GitHub for version control and collabora􀆟on.
13. Secured applica􀆟on communica􀆟ons using a Cer􀆟ficate Manager.
14. Configured Simple No􀆟fica􀆟on Service (SNS) to alert about ac􀆟vi􀆟es within the Auto Scaling Group.
15. Registered the domain name and set up a DNS record using Route 53.
