# NOTES

<style>
b { color: RoyalBlue }
r { color: Crimson }
o { color: DarkOrange }
g { color: SeaGreen }
y { color: Gold }
</style>

## The AWS Global Footprint

- <b>Region</b>
  - separate geographic area hosting AWS data centers.
  - provide fault tolerance and stability.
  - allow you to deploy workloads in multiple locations around the world.
- <b>Availability Zone (AZ)</b>
  - isolated, independent data center within a region.
  - have redundant power, networking, and low-latency connectivity.
  - physically separate from other AZs in the same region to provide high availability and
    fault tolerance.
- <b>Edge Location</b>
  - AWS data centers to help deliver content to end users with low latency.
  - Closer to end users compared to regions and AZs.
  - Leverage <y>Points of Presence</y> (PoPs) to cache content
    and provide faster access to applications and services.
