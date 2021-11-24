# Elastic Block Storage (EBS) - Block Storage

Dedicated hard-disk for a machines.

- In block storage, files are separated into equal-sized pieces(blocks) of data

### Why don't we replicate EBS in another regions

- NO, we are recommended to create a snapshot, and it would replicate to another regions
- EBS has to stand on the same availability zone(AZ)