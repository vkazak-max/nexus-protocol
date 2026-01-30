# London Root Hub
## Reference Implementation for NEXUS Protocol

Status: Reference Implementation  
Scope: Non-normative  
Location example: London, UK

---

## 1. Purpose

London Root Hub is a **reference implementation** of NEXUS Protocol.
It demonstrates how a federated coordination node can be deployed
without central authority, ownership, or control over participants.

This document describes an example, not a requirement.

---

## 2. Role in the Federation

The London Root Hub serves as:

- a coordination reference
- a discovery and interoperability node
- an example of federation-compatible infrastructure

It does NOT:

- control traffic
- own networks or uplinks
- enforce participation
- act as a mandatory gateway

---

## 3. Why London (Example Rationale)

London is used as an example due to:

- high international connectivity
- strong infrastructure redundancy
- legal and regulatory clarity
- neutral positioning between regions

Other locations may provide equivalent or superior implementations.

---

## 4. Functional Components

### 4.1 Identity and Discovery
- public registry of node identifiers
- cryptographic key-based identity
- no KYC or personal data

### 4.2 Overlay Coordination
- encrypted node-to-node connectivity
- federation signaling
- no inspection of user traffic

### 4.3 Governance Interface
- DAO coordination endpoints
- proposal and signaling support
- no unilateral decision-making power

### 4.4 Optional Services
- monitoring (opt-in)
- public mirrors of protocol documents
- reference dashboards

---

## 5. Architecture Overview

