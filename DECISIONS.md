# Synapse — Assessment Decisions

## Product direction

The page presents Synapse as an AI research workspace that maps relationships among papers, concepts, methods, findings, and evidence.

The product intentionally differs from a conventional AI chat interface: the research map is the primary interface and demonstrates the product immediately.

## Scope

This is a frontend assessment, so the page uses deterministic demo data. It does not claim that an LLM is running behind the demo. A production implementation could add a paper-ingestion and extraction layer that identifies entities and relationships from research documents.

## Interaction

The primary interaction is selecting a concept in the research map. The selected node updates the detail panel with a description, paper count, method count, and connected ideas. This was chosen because it directly demonstrates the core product proposition instead of adding decorative animation.

## Visual direction

The visual system uses restrained neutrals, a single blue-violet accent, thin borders, structured panels, and graph-like lines/nodes. The intent is analytical and research-oriented rather than using a generic AI gradient aesthetic.

## Honesty

All paper counts and graph data are explicitly demo workspace data. No fabricated customer numbers, testimonials, adoption claims, or logos are used.

## Verification

The implementation is a self-contained static page and should be checked at both desktop and mobile widths before final submission. The primary responsive target is 390px and the desktop target is 1440px.
