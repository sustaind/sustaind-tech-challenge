# Sustaind Platform/DevOps Engineering Challenge

## Overview

The role of a platform engineer it to empower engineering to ship value fast and reliably.
The nature of the challenges you're expected to face are, for example the following:

- Enable engineers to ship value fast and reliably;
- Sync data sources in way that enable fast and reliable data consumption;
- Manage infrastructure and provide abstractions so that engineers can focus on building features while being able to monitor and troubleshoot their applications;
- Technically advise on infrastructure choices based on business requirements.

This role is to work closely with product and data teams to enable seemless integration between the different products and data sources while improving the DX (Developer Experience) for the engineers so that development can take place in an environment where innovation is possible without sacrificing stability and reliability.

## The challenge

Imagine you're in a meeting with the Architect and the Product Owner to discuss the future of the platform, and we have the following requirements:

- We build features that store data in a database that might be re-used by other features or even other parts of the system;
- This data needs to be kept in sync and depending on the nature of the data, it might need to be synced in real-time or near real-time;
- Depending on frequency of the data updates, the data might need to be synced daily, weekly or monthly;
- How to provide tools to visualise and troubleshoot the data in the system while being able to develop features in a self contained way.

How would you come up with a solution to this problem?

### How to approach this problem

In this challenge the goal is to learn as much as possible about your way of working and how you would approach a problem like this. What kind of questions you would ask? What kind of constraints you would consider? What kind of assumptions you would make?

The challenge is open ended and there are no right or wrong answers. It's important to explain your reasoning and how you would go about solving the problem.

### Expected output

The output should be a proposal for a solution to the problem above. It should include:

- A description of the problem and the constraints associated with it;
- A description of the solution you would propose;
- A high-level architecture of the solution;
- A list of assumptions you would make;
- A list of questions you would ask.

Technically you can build a small PoC to showcase the solution that takes into account that we're using ECS in AWS - but overall docker and containers is the important aspect of this challenge - not the specific technology of where these are ran.

A representation on how to build a small scale replica of such a system and how would observability, monitoring and troubleshooting be implemented along with DX implications.

## Evaluation criteria

- Technical correctness;
- Architecture design;
- DX implications;
- Observability, monitoring and troubleshooting;
- Cost;
- Scalability;
- Reliability;

Overall the solution should be a good fit for the problem and the constraints - you can define your own constraints as long as you justify why you defined them as such.

## Submission

Use the repository as a template and send us the link to the repository with your solution. The original README should be preserved - create other markdown files to document your solution.














