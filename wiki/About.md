---
type: "Overview"
title: "About this export"
description: "What this export is and how to read claim status, evidence class, and citations"
tags:
  - "overview"
---

# About this export

A read-only, citation-backed export of Polity Ancestry: entities,
relationships, and transitions assembled from public records, with the
claim status, evidence class, and citation shown on relationship
rows when present in the stored source record.

## Reading the data

- Every connection shows how strongly its claim is supported (Claim), the kind of evidence behind it (Evidence), and its citation.
- Claim strength here, strongest first:
  - **tentative** — a lead from reference data, awaiting evidence
- Kinds of evidence here: reference work.
- Two evidence layers form the graph: political succession (one polity giving way to another) is the flow, and political containment (an empire to its constituent polities) is a section layer on entity pages. Both point from an ancestor toward a descendant. Rulers, places, and cultural transmission are outside this graph.
- Wikidata supplies identity, envelope metadata, and weakest-tier succession and containment leads (candidate/tertiary): an edge cited only to Wikidata is the weakest claim, awaiting curated source evidence to strengthen it.
- Membership comes from the census roster's class predicate — antiquity through the present — not from hop-by-hop traversal; undated polities are members like any other.
- Entity-resolution notes ("suspected same as") are unreviewed resolver hints, not evidence.

## Contents

- Entities: 7455 polity
- Transition pages: 0

| Relationship | Count |
| --- | --- |
| transitioned to | 2704 |
| has part | 591 |
