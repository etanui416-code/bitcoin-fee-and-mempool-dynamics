
# Bitcoin Fee and Mempool Dynamics

This repository documents my study of how Bitcoin transaction fees,
mempool behavior, and block assembly interact.

Understanding fee dynamics is critical for wallet design, fee estimation,
and network reliability under congestion.

## Topics Covered
- Mempool admission and eviction policies
- Fee rate calculation and estimation
- Child-Pays-For-Parent (CPFP)
- Replace-By-Fee (RBF)
- Miner transaction selection behavior

## Security and Reliability
Fee and mempool logic directly affect transaction confirmation,
network load, and user experience. This repository focuses on
edge cases and failure scenarios.

## Methodology
- Study Bitcoin Core mempool code paths
- Review historical PRs and BIPs
- Analyze real-world congestion events

## Status
Research notes updated incrementally.
