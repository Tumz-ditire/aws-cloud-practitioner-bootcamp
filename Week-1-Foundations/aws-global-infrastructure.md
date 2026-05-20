## What is a Region?
- A Region in AWS, is simply a specific part of the world where Amazon has built several state‑of‑the‑art data centers. These facilities work together to deliver cloud services that are fast, reliable, and compliant with local regulations. Think of it like a hub: AWS places multiple secure buildings in one geographic area so customers nearby get better performance, stronger backup options, and assurance that their data stays within the right legal boundaries. Therefore a Region is like a "city" for example Cape Town and N.Virginia. That is completely isolated from other "cities" or Regions.



## What is an Availability Zone?
- An Availability Zone is basically one or more data centers inside an AWS Region. Think of it as separate “buildings” within the same geographic hub, each designed to run independently but connected with super-fast private links. Therefore Inside that city, AWS has several data centers (called Availability Zones), which are like different “neighborhoods.” By spreading resources across these "neighborhoods", AWS ensures reliability, speed, and backup options if one data center has issues.



## Why AWS uses multiple AZs?
- Each AZ is in a different location to avoid shared risks. They have their own power, cooling, and networking, so one outage doesn’t affect the others.
AZs are linked with private, low-latency networks so they can work together seamlessly. An example is the Cape Town Region (af-south-1), you’ll see AZs like: (af-south-1a) and (af-south-1b). Each is a distinct data center setup within that Region. AZs are reliable because your applications stay online even if one AZ has issues. Problems in one AZ don’t spill over into others.



## Basic idea of global infrastructure?
- AWS Global Infrastructure is the worldwide network of advanced facilities and systems that Amazon has built to run its cloud. It’s the backbone that makes it possible for AWS to deliver services anywhere in the world with speed, reliability, and strong security.
- Think of it like a global power grid: AWS has set up interconnected hubs across continents so businesses can plug in and get consistent, high-quality service -whether they’re in New York, Cape Town, or Tokyo.

---
