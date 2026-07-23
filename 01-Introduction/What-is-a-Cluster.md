## What is a Cluster?

A **cluster** is a group of two or more servers (called **nodes**) that work together as a single system to provide high availability, improved performance, and scalability. 

Clusters are widely used in production environments where continuous service availability is critical, such as banking, healthcare, e-commerce, telecommunications, and cloud infrastructure.

---

## Why Do We Need a Cluster?

A single server can become a single point of failure. If the server experiences hardware failure, operating system crashes, or scheduled maintenance, the hosted application becomes unavailable.
A cluster eliminates this risk by distributing services across multiple servers, allowing another node to continue serving users if one node becomes unavailable.

---

## Purpose of a Cluster

- **High Availability (HA):** Ensures applications remain available even if a server fails.
- **Load Balancing:** Distributes client requests across multiple servers to improve performance.
- **Scalability:** Allows additional servers to be added as demand increases.
- **Disaster Recovery (DR):** Helps maintain business continuity during failures or disasters.

---

## Key Components

- Nodes
- Pacemaker
- Corosync
- PCS (Pacemaker Configuration System)
- Shared Storage (optional)
- Virtual IP (VIP)

---

## Advantages

- High Availability
- Automatic Failover
- Reduced Downtime
- Improved Reliability
- Easier Maintenance
- Better Resource Utilization

---

## Disadvantages

- More complex to configure
- Higher infrastructure cost
- Requires continuous monitoring
- Proper fencing (STONITH) is recommended in production environments

---

## Real-World Examples

- Banking applications
- Online shopping platforms
- Hospital management systems
- Airline reservation systems
- Cloud platforms

---

## Summary

A cluster combines multiple servers into a single logical system to improve availability, reliability, and scalability. By eliminating single points of failure, clustering ensures that business-critical applications continue running even when individual servers experience issues.
