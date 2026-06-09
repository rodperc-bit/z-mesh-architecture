# English version

This folder contains the English adapted version of the Z-MESH v0.1 position paper.
Z-MESH Architecture

Z-MESH — Zero Trust Micro-MCP Ephemeral Sandbox Hub is a conceptual architectural proposal for secure governance of MCP capabilities driven by AI agents.

The proposal introduces the concept of ephemeral Micro-MCPs running in isolated sandbox runtimes, with policy evaluation, temporary credentials, traffic restriction, contextual auditing and destruction of the runtime after execution.

Document Title: Z-MESH: a Zero Trust architecture proposal for ephemeral Micro-MCPs in distributed sandbox runtimes Zenodo, v0.1, 2026. DOI: 10.5281/zenodo.20600003

Author: Rodrigo Persiani Ciscom Collaborator: Rogerio Alves de Macedo

Version: v0.1 Type: Position Paper / Architectural Proposal Status: Initial version for technical discussion, experimental validation and academic collaboration Repository structure paper/ Main document in PDF and DOCX diagrams/ Architecture figures and diagrams hashes/ SHA-256 hashes of published files lab-proposal/ Future proposal for experimental validation Objective

The goal of Z-MESH is to propose a complementary Zero Trust governance layer to mediate AI agents' access to sensitive enterprise systems through ephemeral, specialized, authorized, and auditable MCP capabilities.

Key Concepts Ephemeral Micro-MCPs: Minimal, specialized, disposable MCP servers. Sandbox runtimes: isolated environments for controlled execution of Micro-MCPs. Z-MESH Concentrator: control plane responsible for authentication, authorization, capability selection, issuance of temporary credentials, traffic control, auditing and destruction of the runtime. Zero Trust Governance: no call is implicitly trusted; each request must be evaluated for identity, purpose, policy, scope and risk. License

The position paper, diagrams and architectural documentation are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

See LICENSE.md for details.

Any future source code or laboratory implementation may be licensed separately.

Quote

A version with DOI may be made available later via Zenodo after the creation of the public release v0.1.
