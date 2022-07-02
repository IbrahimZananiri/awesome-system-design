# Design Uber, a ride-hailing system

## Challenge

Have you ever wondered what goes behind the scenes when you simply tap to request an Uber ride, get matched with a driver, to get you from one location to another, all through your mobile device?

Let’s design the architecture for a ride-hailing system like Uber or Lyft!


### Requirements
- A rider requests a ride to their chosen location
- The rider is matched with a driver/ride who accepts to take the ride, and starts to see trip updates on a map
- Driver drops the rider off at their chosen destination and the system charges the rider.
- Routes are recorded and persisted for safety and to enable the experience.
- The system should determine and notify nearby drivers within less than 100ms


### Scale of the System
- 500 million riders
- 10 million drivers
- 1 million concurrent users
- 25 million trips daily

# Proposal

> **EDIT ME**: Your design proposal goes here!\
> Use this file as the template for your proposal.

# Featured Proposals

- [IbrahimZananiri's Proposal: Design Uber, a ride-hailing system](/challenges//uber/proposals/IbrahimZananiri)

---

# Submit Your Design Proposal

1. Fork repo
2. Create your `proposals/{GITHUB_USERNAME}/` directory
3. Write your proposal in README.md
4. Submit a PR for review!

More details on [/challenges/CONTRIBUTING.md](/challenges/CONTRIBUTING.md)
