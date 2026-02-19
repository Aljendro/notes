# NOTES

## The AWS Global Footprint

- Region
  - separate geographic area hosting AWS data centers.
  - provide fault tolerance and stability.
  - allow you to deploy workloads in multiple locations around the world.
- Availability Zone (AZ)
  - isolated, independent data center within a region.
  - have redundant power, networking, and low-latency connectivity.
  - physically separate from other AZs in the same region to provide high availability and
    fault tolerance.
- Edge Location
  - AWS data centers to help deliver content to end users with low latency.
  - Closer to end users compared to regions and AZs.
  - Leverage **Points of Presence** (PoPs) to cache content
    and provide faster access to applications and services.
