# Prompt for `fireworks-tech-graph`: PRD Writing Toolkit Workflow

Create a production-quality README diagram for the `PRD Writing Toolkit` repository.

## Objective

Visualize this repository as an end-to-end operating system for product requirement work:

1. start from messy business inputs
2. draft with `create-prd-skill`
3. review with `check-prd-skill`
4. close the loop in Feishu/Lark
5. make a real delivery-gate decision

The diagram should make the toolkit feel like a professional product workflow, not a loose pile of prompt files.

## Audience

- B2B product managers
- product ops and review owners
- AI-native teams evaluating whether this repo is credible and reusable
- GitHub visitors scanning quickly on a README page

## Diagram Type

- Use an `architecture` diagram with process-flow semantics
- Landscape layout for GitHub README embedding
- Style: `6` (`Claude Official`)
- Export both SVG and PNG

## Narrative to Encode

- `Business Inputs` are the starting signal
- `create-prd-skill` turns raw context into a structured `PRD Draft`
- `check-prd-skill` reviews the draft with chapter-based or fallback logic
- `Feishu Assistant` pushes findings back into Feishu/Lark, tracks confirmations and waivers
- `Delivery Gate` is the final readiness decision
- `prd-quality-framework` is the foundational layer that guides create, check, and Feishu collaboration

## Layout

- Four phase containers across the top row:
  - `01 Signal Intake`
  - `02 Draft Authoring`
  - `03 Quality Review`
  - `04 Collaboration Gate`
- One full-width bottom container:
  - `05 Foundation`
- Keep strong whitespace and straight orthogonal routing
- No arrow should cross through node interiors
- Keep the visual hierarchy obvious in one glance

## Node Guidance

- `Business Inputs`: source node, soft blue
- `create-prd-skill`: key active module, double-rect
- `PRD Draft`: document-shaped artifact
- `check-prd-skill`: key active module, double-rect
- `Findings Pack`: review output node
- `Feishu Assistant`: collaboration node tied to `feishu-prd-review-loop`
- `Delivery Gate`: decision/gate shape
- `prd-quality-framework`: wide foundation block with standards summary

## Arrow Semantics

- `control`: primary workflow progression
- `data`: findings and recommendations output
- `read`: framework guidance flowing upward into the active skills
- Include a legend because multiple flow semantics are present

## Text Constraints

- Keep arrow labels to one short verb or phrase
- Keep node titles readable at GitHub README scale
- Subtitle should communicate: drafting, reviewing, and closing the loop in Feishu/Lark

## Visual Constraints

- Warm, polished, documentation-grade
- More premium than Mermaid
- No dark background
- No unnecessary decoration
- Must still feel crisp when scaled down in GitHub markdown

## Deliverables

- `assets/diagrams/prd-writing-loop.json`
- `assets/diagrams/prd-writing-loop.svg`
- `assets/diagrams/prd-writing-loop.png`
