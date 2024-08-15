# 3-Tier_Architecture-on-AWS
🚀 Building a Scalable Three-Tier Architecture on AWS Free Tier 🚀

I recently implemented a simple and cost-effective three-tier architecture on AWS using only free-tier services. Here’s a quick breakdown of how I did it:

🔸 Tier 1: Presentation Layer (Web Frontend)
Service: EC2 (t2.micro - free tier eligible)
I deployed a web server running on an EC2 instance, hosting the front-end application. It handles user requests and serves the static content.

🔸 Tier 2: Application Layer (Logic Processing)
Service: EC2 (t2.micro - free tier eligible)
A separate EC2 instance running the business logic, communicating with the front-end and database. I used a basic load balancer for high availability.

🔸 Tier 3: Data Layer (Database)
Service: Amazon RDS (free tier eligible)
I set up an Amazon RDS instance running MySQL as the database, managing user data securely and reliably.

All of this was achieved within the constraints of the AWS Free Tier, allowing for experimentation without incurring any charges. 🎯

💡 Bonus Tip: Remember to leverage AWS security best practices by using Security Groups, IAM roles, and encryption to protect your resources & Make SSM service for better practices.

#Work-Flow Diagram : 

![3TierArch,png]
