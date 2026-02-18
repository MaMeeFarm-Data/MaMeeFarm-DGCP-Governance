# DGCP™ Governance Record
Date: 2026-02-18
Subject: Proof–DataUnit Reference Policy Clarification
Status: Active
Scope: Evidence / Proof Layer Separation

---

## 1. Background

During daily logging operations, Proof entries were sometimes linked to the latest DataUnit of the same day, even when the contextual relationship was indirect (e.g., inverter shutdown DU referenced by unrelated Proof event).

This document clarifies reference rules moving forward.

---

## 2. Policy Statement

Effective 2026-02-18:

1. A Proof may reference a DataUnit only if:
   - There is direct contextual continuity, OR
   - There is operational dependency, OR
   - There is time-sequential relevance that affects interpretation.

2. A Proof shall NOT reference a DataUnit solely because:
   - It is the latest DU of the day.
   - It shares the same calendar date.
   - It appears sequential in numbering.

3. If no direct DU relevance exists:
   - The Proof shall stand independently.
   - No artificial linkage shall be created.

---

## 3. Layer Separation Principle

DGCP™ maintains strict structural separation:

- DataUnit Layer → Raw event record.
- Proof Layer → Verifiable evidence object.
- Governance Layer → Structural rule definition.
- Legal Layer → Rights and license control.

No layer may override the structural integrity of another.

---

## 4. Retroactive Adjustment Rule

Past records remain historically intact.

If structural inconsistency is later identified:
- It shall be recorded in Governance.
- It shall NOT be silently rewritten.
- Audit-based correction is permitted.
- Historical rewrite is prohibited.

---

## 5. Operational Impact

This clarification reduces:
- Artificial cross-layer linkage
- Commit confusion
- Sequential dependency errors

System integrity remains intact.

---

DGCP | MMFARM-POL-2025
