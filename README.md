# Final-Presentation

# Title: Adopting Microservices at Netflix: Lessons for Team and Process Design

Adrian Cockcroft was one of the key architects when Netflix moved away from their own data centers and towards Amazon’s cloud services, AWS. He helped to migrate them to a cloud-native architecture and established NetflixOSS, which is open source software to help other companies build similar cloud infrastructure. 
In 2008, Netflix was operating on high-end IBM hardware and Oracle database. They experienced a two day outage due to hardware failure because they assumed their hardware/software wouldn’t fail. This resulted in Netflix thinking more about their service availability and how to handle failures. Since availability became an application concern, they wanted to explore the idea of using a lower cost cloud infrastructure instead of the high-end data centers. 
	
The outage was not going to be the event that single-handedly pushed Netflix to move to cloud infrastructure because it was a new concept. In 2009, they needed to heavily increase their data centers capacity because their online streaming service was largely outweighing their DVD shipping service (remember that?). They were unsure of how much they needed to increase the power of their data centers, how much it was going to cost them, and where the data centers were going to be located to optimize their availability. It is similar to how IT departments were often scaled to how many employees a company had and not optimized for how many customers they had or will have in the future. 
	
In the beginning with the DVD business, customers would only interact with Netflix’s website maybe a few times a week at most to select movies and have them shipped to their house. Customers were limited to how many movies they would rent per week. But once the streaming service gained more traction, customers were able to interact with Netflix everyday for longer periods of time or multiple times per day. There’s also way more information that Netflix’s data centers need to keep track of with the streaming service like user preferences, progression through the media, quality of the streaming, etc. So those factors combined put a very heavy workload onto the data centers. Adrian Cockcroft saw that there were two options on how to fix this new problem. Either spend a ton of money upfront for building top of the line data centers and guess how much capacity they would need before it was even built, or they could utilize services within AWS, built by Amazon which was one of Netflix’s biggest competitors, but they could focus their funds onto the actual content of the website and developers. They decided on the second option and needed to make the move to AWS before 2010 in order to keep their customers. They moved the front end to the cloud while they kept most of the backend in data centers by the end of 2010. Adrian references that they treated the timeline of 2010 as an airplane on a runway taking off: they needed to get the airplane (Netflix) off the ground and into the sky (the cloud) before they ran out of runway (before the end of the year). 
	
The main takeaway of the migration to AWS was they focused on gradual migration at first to make sure that it was going to work out and by the end, Netflix had to go all in on the cloud and close their data centers so there was no turning back. 
	
# Sources:
https://www.datacenterknowledge.com/archives/2016/10/25/cockcroft-the-man-behind-netflixs-move-to-aws-joins-aws

https://www.datacenterdynamics.com/en/news/netflix-ebay-alum-adrian-cockcroft-joins-aws-as-vp-of-cloud-architecture/

https://projecttoproduct.org/podcast/adrian-cockcroft/ 

https://www.youtube.com/watch?v=XrWII4ewrXA 
