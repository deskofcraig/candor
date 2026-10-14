# Step 1: Structure Your PRD with an AI-Friendly Framework

## Task / Objective: 
`State the core goal of the screen or flow in one sentence (e.g., "Create a mobile activity-tracking dashboard for users to log daily steps and view weekly charts.").`

Create an application called "Candor" that helps people applying for work receive better feedback when being unsuccessful when looking for work. "Candor" will also help recruiters and talent acquisition better assess candidates against job description categories.

For Recruiter and Talent Acquistion:
- Recruiters can state a full job description for a role vacancy into and judge applicants by content and context discovered in their cover letter, resume, and cv.
- The job description generates category benchmarks that applicants are judged and scored against. These benchmark categories can be manually adjusted by recruiters if need be.
- Applicant applications can be uploaded to the job description for analysis. This will collect and generate a profile based on uploaded material such as cover letter, resume, and cv.
- Applicants are scored against benchmarks, and can see how applicants rate against the benchmark.
- Stronger applicants can be automatically collected and flagged against benchmarks for recruiters.
- A recruiter can highlight a chosen number of top applicants. ie. "group the top 20 applicants" 
- Benchmarks value sets can be updated based on top applicant ratings as a new version of bench marking. Previous sets for a job description are still visible by selecting a version. This is non destructive.
- An individual applicant can be selected to see how they rate against benchmarking.
- The average rating of all applicants can be selected to see against benchmarking.
- Single button notification of successful and unsuccessful candidates.
- Recruiters can add stages for recruitment processes. ie. Screening interview, 1st Round interview, Technical interview, etc.
- Job descriptions can not be editted once posted.
- Recruiter can add an application deadline time and date to thier listing.
- Job description listing can be ended or closed for applications early.

For Applicants and Candidates:
- A candidate can see the job description in full and key category benchmark ratings before starting an application.
- A candidate can upload their application for preview against the job description benchmarking to see how they rate before confirming their application.
- When notified of being unsuccessful, they are emailed feedback on the metrics of their application against the job description and other candidates ratings. The goal is the help unsuccessful candidates pin point areas of improvement, details to include or consider for next time, and what successful candidates did or had that was different to them.
- For Applicant view, they can see how they rated in against:
  - successful applicant average.
  - successful applicant base line and range.
  - initial job description benchmarking and its version if they exist.
- All other candidate personal details and contact details are anonymised for privacy and security.
- Other context can to deleivered outside of the benchmarking catergories it appears in successful candidate profiles.
- Give applicants to option to view a parsed version of their application materials one by one so they can review and see if they need to make changes or fix errors before completing application. Changes will re-analysis their application material. This will help with automated text system readers and make sure the current is correct to the applicant. 
- If unsuccessful at the initial application stage, send applicants a parsed version of their application materials so they can review and see if they need to make changes or fix errors before completing application. Changes will re-analysis their application material. 
 


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




