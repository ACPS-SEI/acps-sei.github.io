---
layout: post
title: Projects
---

This site list the projects that the ACPS directorate has developed including architectural analysis tools, CPS analysis closer to the code level, and execution environment such as real-time schedulers and the corresponding analyses and verified hypervisors.

 Architectural design and analysis techology comprises, first the Open-Source-AADL-Tool-Environment (OSATE) that can be obtain from its own independent site: [OSATE Site](https://osate.org).

# Architectural Model/Analysis tools

## Oqarina

Oqarina is a mechanization of AADL using Coq. It provides a set of capabilities to represent an AADL model using Coq types and perform some processing. It is presented in [this page](tools/oqarina)

# Execution and Behavioral Analysis

## Real-Time Mixed-Trust Computation

The real-time mixed-trust computation framework is a real-time runtime environment and analyses tool to enable the enforcement-based verification by the creation of mixed-trust real-time tasks with unverified components guarded by verified components that execute in a verified hypervisor. [this page](tools/mixed-trust)

# Automatic Certification 

## Symbolic Assurance Refinement

Safety-Critical Systems require certification before deployment. Unfortunately, current certification practice is manual, slow, and error prone. In this project we developed the Symbolic Assurance Refinement framework that uses formal methods to automate the verification procedures, their assumptions and the integration of the evidence they produce into a deductive argumentation that can be formally evaluated to discharge certification claims.  [this page](tools/sar)