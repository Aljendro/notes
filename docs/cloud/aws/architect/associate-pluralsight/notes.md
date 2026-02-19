# NOTES

<style>
bl { color: royalblue; font-weight: bold }
re { color: crimson; font-weight: bold }
or { color: darkorange; font-weight: bold }
gr { color: seagreen; font-weight: bold }
ye { color: gold; font-weight: bold }
pi { color: orchid; font-weight: bold }
</style>

## The AWS Global Footprint

- <bl>Region</bl>
  - separate geographic area hosting AWS data centers.
  - provide fault tolerance and stability.
  - allow you to deploy workloads in multiple locations around the world.
- <bl>Availability Zone (AZ)</bl>
  - isolated, independent data center within a region.
  - have redundant power, networking, and low-latency connectivity.
  - physically separate from other AZs in the same region to provide high availability and
    fault tolerance.
- <bl>Edge Location</bl>
  - AWS data centers to help deliver content to end users with low latency.
  - Closer to end users compared to regions and AZs.
  - Leverage <ye>Points of Presence</ye> (PoPs) to cache content
    and provide faster access to applications and services.
