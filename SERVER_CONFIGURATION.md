# Primary Configuration

Our primary infrastructure will consist of a witness node and 3x full nodes, co-located in a Data Centre based in Manchester, UK.

The sentry node acts as guardians for the witness node, which is isolated from the main network.

| Witness Node |                            |
| ------------ | -------------------------- |
| CPU          | 32 Cores                   |
| Memory       | 128 GB                     |
| OS/SSD       | 240 GB                     |
| HDD          | 4TB (RAID 10 - 2TB usable) |
| Network      | 10Gbps                     |

| Full Node / Sentry |                            |
| ------------------ | -------------------------- |
| CPU                | 16 Cores                   |
| Memory             | 64 GB                      |
| OS/SSD             | 240 GB                     |
| HDD                | 4TB (RAID 10 - 2TB usable) |
| Network            | 10Gbps                     |

# SECONDARY Configuration

As a secondary configuration in-case of a disaster involving our primary infrastructure, we have a backup witness node running on AWS.
