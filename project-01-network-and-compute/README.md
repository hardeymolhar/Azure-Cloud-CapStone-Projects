## Terraform Structure (Context)

This project was implemented as a **single-directory Terraform configuration**, with resources separated across logical files (network, firewall, routes, compute).

At the time of implementation, this was my **first hands-on Terraform project**, and the structure reflects a deliberate focus on:
- understanding resource relationships
- managing dependencies explicitly
- learning state handling and remote state consumption

Modularization was intentionally deferred to prioritize correctness and comprehension over abstraction.


## What I Would Refactor Next

With deeper Terraform experience, this project would evolve to:
- extract network components into reusable modules
- formalize input/output contracts
- introduce environment-specific variables
- add CI validation for plan/apply

The current structure represents an early but functional stage in that progression.
