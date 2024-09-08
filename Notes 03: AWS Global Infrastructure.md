# CIT 114
## Notes 3
### AWS Global Infrastructure
1. Summarize a few key points made in the readings or videos.
   - AWS Regions are distributed around the world so that customers can choose a region closest to them in order to host their cloud infrastructure there.
     - Each region has multiple AZs and when you design your infrastructure to have backups of data in other AZs you are building a very efficient model of resiliency, i.e. a core concept of cloud computing.
     - Endpoints are specific URLs that act as an entry point for a web service, and many AWS services will have an endpoint based on its region/AZ.
2. Identify and provide two quotes that were made in the readings or videos, that you found interesting. Describe why you found each quote of them interesting.
   - Two quotes "I found interesting were Endpoints aim to reduce further the latency of your applications, but not all AWS services support endpoints with regions/AZ data in the naming convention." and "AWS 
     Infrastructure is elastic and scalable. This means resources can dynamically adjust to increases or decreases in capacity requirements. It can also rapidly adjust to accommodate growth."
     - I found these quotes interesting the first quote informs us about AWS services support system, and the second quote explains growth and increase capacity the AWS Infrastructure requires.
3. Outline the new facts that you learned from this section?
   - The closer your region is to you, the better, so that you can reduce network latency as much as possible for your end-users. You want to be near the data centers for fast service.
     - AWS Local Zones are a new type of AWS infrastructure deployment that places AWS compute, storage, database, and other select services closer to large population, industry, and IT centers.
     - Each AWS Local Zone location is an extension of an AWS Region where you can run your latency-sensitive applications using AWS services.
4. What questions remain in your mind after reading this section?
   - Not much, I felt like I learned a lot from this section and readings/ videos.
