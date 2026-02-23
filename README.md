Laatuhieronta.fi — Entity Data Layer

This repository contains the machine-readable structural data layer for the Laatuhieronta.fi operational compliance system.

It defines semantic entities using JSON-LD aligned with schema.org standards.

The purpose of this repository is to expose a stable, structured representation of the system for search engines, knowledge graphs, and AI agents.

What this repository is

This is not an application.

This repository is a semantic data layer that describes:

• the organization entity
• the operational system entity
• service and documentation entities
• regulatory context entities
• page-level semantic definitions

All data is provided as JSON-LD to enable machine readability.

Why this exists

Traditional websites present information primarily for humans.

This repository provides the same system as structured entities designed for:

• entity-based search indexing
• semantic web integration
• AI knowledge extraction
• long-term data stability

It acts as a canonical reference layer for the system’s identity and structure.

Structure Overview
Core Entities

/entities/organization.jsonld
Defines the organizational entity.

/entities/website.jsonld
Defines the website entity.

/entities/solution-omavalvontajarjestelma.jsonld
Defines the operational compliance system as a service entity.

Page Entities

/entities/page-*.jsonld

Each page entity provides semantic descriptions for:

• purpose
• relationships
• regulatory scope
• operational context

Supporting Entities

Additional files define relationships such as:

• regulatory references
• documentation frameworks
• operational components

Design Principles

The entity structure follows these principles:

Stability over presentation

Entities represent core meaning rather than UI structure.

Machine-first readability

All definitions prioritize semantic clarity.

Canonical reference model

This repository serves as the authoritative entity source.

Separation of layers

The semantic layer is independent from the website implementation.

Use Cases

This data layer supports:

• search engine entity recognition
• knowledge graph integration
• AI agent contextual understanding
• semantic indexing of operational systems

Relationship to the live system

The public interface of the system is available at:

https://laatuhieronta.fi

This repository represents the underlying semantic structure that describes it.

Repository Scope

This repository intentionally contains only:

• JSON-LD entity definitions
• minimal structural documentation

It does not include:

• application code
• business logic
• UI components

Maintainer

Maintained as part of the structural infrastructure for the Laatuhieronta operational compliance system.
