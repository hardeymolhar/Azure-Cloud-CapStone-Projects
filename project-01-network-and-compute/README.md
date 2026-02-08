## (Context)

This project was implemented as a **single-directory Terraform configuration**, with resources separated into logical files (network, firewall, routes, compute).

As this was my **first hands-on Terraform project**, the structure reflects a deliberate focus on:
- understanding resource relationships
- managing dependencies explicitly
- learning Terraform state handling and remote state consumption

Modularization was intentionally deferred to prioritize **correctness and comprehension** over early abstraction.

---

## What I Would Refactor Next

With deeper Terraform experience, this project would evolve to:
- extract network components into reusable modules
- formalize input/output contracts between layers
- introduce environment-specific variables
- add CI validation for `terraform plan` and `apply`

The current structure represents an **early but functional stage** in that progression.
