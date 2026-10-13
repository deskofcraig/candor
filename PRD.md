# Step 1: Structure Your PRD with an AI-Friendly Framework

## Task / Objective: 
`State the core goal of the screen or flow in one sentence (e.g., "Create a mobile activity-tracking dashboard for users to log daily steps and view weekly charts.").`


## Output Specification: 
`Define the exact deliverables you expect from Figma (e.g., "A 3-screen interactive prototype covering Empty State, Active Data State, and Error/Offline State").`


## Key Elements
`List every UI component required on the screen (e.g., header, top navigation bar, primary metric card, data table, bottom tab bar).`


## User Behaviors & Flows
`Describe what happens on interaction (e.g., "When the user taps 'Add Workout', a bottom sheet slides up with a weight input field").`


## Notable Constraints & Edge Cases
`Call out hard limits (e.g., "Table must support up to 50 characters in a single column without text truncation breaking the layout; use 8px spacing grid").`


---

# Step 2: Ground the PRD in Your Design System

AI models drift when they have to guess your styling rules. Link or embed concrete design system parameters directly into your PRD:

## Design Tokens Reference
`Specify your primitive or semantic tokens for colors, font families, type scale, border radius, and spacing.`

## Reference System Link
`Point the AI to your existing Figma library frame, or upload a structured design .md / style guide file.`

## Visual Anchors
`Attach reference screenshots or mood-board links for layout inspiration so the AI doesn't invent random component patterns.`


---

# Step 3: Write a Master Prompt to Feed the PRD into Figma

When you pass your PRD into Figma Make or connected tools (like Notion integrations), avoid polite or vague conversational fluff. Use a direct, recipe-card style prompt:
“Read the attached PRD [link doc/file]. Generate the core user flow screens for [Project Name] adhering strictly to our design system tokens in [Figma Frame Link]. Prioritize layout structure for [State 1] and ensure component anatomy matches the specs before adding micro-interactions.”

---

# Step 4: Iterative Refinement Checklist

## Front-load structure
`A well-scoped PRD cuts down prompt iterations drastically (moving from dozens of messy trial-and-error prompts down to a clean baseline).`

## Test state by state
`Don't ask the AI to build an entire multi-step app in one single prompt. Generate foundational shells first (navigation, base grids), then layer in complex tables, states, and mobile responsiveness.`

## Audit against constraints
`Check the AI output immediately against your edge cases (e.g., long text strings, missing data, error states) before handing the design off or exporting code.`


---

If you'd like, share what type of product or screen you are trying to design (e.g., SaaS dashboard, e-commerce checkout, mobile app), and I can help you draft a custom PRD template tailored for AI generation.




