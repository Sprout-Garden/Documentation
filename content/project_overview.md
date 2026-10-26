---
title: Project Overview
draft: false
---

This page introduces the Sprout Garden System, its scope, and the people and external systems it serves. Keep detailed implementation decisions and low-level designs in the corresponding source-code repositories.

## Purpose

Currently the greenhouse is maintained entirely through manual labor. To reduce the need for manual intervention, a system shall be developed to collect environmental data and automate gardening tasks where possible. Initially the system shall monitor the greenhouse and manage irrigation. However the system is designed with scalability in mind allowing additional areas or devices to be integrated in the future.

## Scope and boundaries![[Sprout-UseCase.png]]

## Key capabilities

- Integration into Home Assistant.
- Environmental Sensors to measure Greenhouse State (Temperature, Soil Moisture).
- Support of multiple zones.
- Irrigation based on sensor data.
- System can be updated by user.

Detailed requirements are documented in [[Requirements]].

## Users

**Garden worker** — The primary user, responsible for greenhouse work and not assumed to be highly technical. The worker uses Home Assistant to view greenhouse conditions and configure or control irrigation.

## Further documentation

See [[System Architecture]] for the system structure, subsystem responsibilities, and their relationships.
