Skill Overview
This skill enables Claude to analyze user interview transcripts and produce high-quality, actionable UX research findings. It synthesizes qualitative data into strategic insights that inform product decisions across domains, markets, and platforms.
When to Use This Skill
Use this skill when you need to:

Analyze user interview transcripts or research session notes
Synthesize qualitative research data into actionable insights
Identify patterns, pain points, needs, and opportunities from user conversations
Generate research findings for product teams, designers, or stakeholders
Transform raw interview data into strategic product direction

Core Capabilities
Analysis Depth

Deep synthesis: Goes beyond surface observations to uncover underlying motivations, mental models, and behavioral drivers
Pattern recognition: Identifies themes across multiple interviews, including contradictions and edge cases
Contextualization: Interprets findings through domain, market, and cultural lenses
Confidence calibration: Flags assumptions, distinguishes evidence strength, notes where data is incomplete

Output Quality

Insight-driven: Prioritizes interpretation over summarization
Actionable: Connects findings to product and design implications
Structured: Organizes insights hierarchically (observations → insights → opportunities)
Professional: Written for product teams, design leads, and executive stakeholders

How to Use This Skill
Basic Usage
Provide Claude with:

Interview transcript(s) or research session notes
Context parameters:

Domain (e.g., "EdTech", "Healthcare", "Enterprise SaaS")
Market/Geography (e.g., "Germany", "Italy", "US", "EU-wide")
Product type (e.g., "Mobile app", "Web platform", "Cross-platform tool")


Optional: Specific research questions or focus areas

Example Prompt
Analyze the attached user interview transcripts using the User Research Analysis skill.

Context:
- Domain: EdTech (childcare management software)
- Market: Germany (DACH region)
- Product: Web-based platform for childcare center administrators
- Focus: Calendar and event management workflows

Produce actionable research findings including user needs, pain points, behavioral patterns, and product opportunities.
Analysis Framework
1. Observation Layer
What users said and did

Direct quotes (used sparingly, for evidence)
Behavioral descriptions
Contextual details
Factual statements

2. Insight Layer
What it means

Underlying needs and motivations
Mental models and expectations
Decision-making criteria
Emotional responses and friction points
Patterns across users
Contradictions and tensions

3. Opportunity Layer
What to do about it

Product implications
Design recommendations
Feature prioritization signals
Strategic directions
Risk areas and constraints

Domain Adaptation
Domain-Specific Considerations
EdTech

Learning outcomes and pedagogical models
Institutional vs. individual user needs
Compliance and curriculum requirements
Parent/teacher/admin role dynamics

Healthcare

Clinical workflows and care coordination
Regulatory compliance (HIPAA, GDPR, MDR)
Patient safety and risk management
Provider vs. patient perspectives

FinTech

Trust and security expectations
Financial literacy levels
Regulatory constraints (PSD2, AML, KYC)
Risk tolerance and decision-making

Enterprise SaaS

Organizational hierarchies and approval flows
Integration with existing tools
Change management and adoption
IT/security requirements

B2C/Consumer

Lifestyle integration
Emotional and social factors
Value perception and willingness to pay
Competitive alternatives

Market/Geographic Adaptation
Germany / DACH Region

Privacy expectations (GDPR, DSGVO)
Preference for thoroughness and documentation
Skepticism toward marketing claims
Formal communication norms
Industry-specific regulations (e.g., KitaG for childcare)

Italy / Southern Europe

Relationship-driven decision-making
Regulatory complexity and bureaucracy
Family and social network influence
Design and aesthetic expectations

United States

Speed and convenience prioritization
Self-service and autonomy preferences
Subscription and pricing sensitivity
Litigious environment considerations

EU-Wide

Multi-language and localization needs
Cross-border regulatory harmonization
Cultural diversity within user base
Accessibility requirements (European Accessibility Act)

Output Structure
Standard Research Findings Report
# Research Findings: [Product/Feature Name]

## Executive Summary
[2-3 paragraph synthesis of key findings and strategic implications]

## Research Context
- Domain: [e.g., EdTech]
- Market: [e.g., Germany]
- Participants: [number, roles, demographics]
- Product context: [brief description]

## Key Insights

### 1. [Insight Theme]
**Observation:** [What users said/did]
**Insight:** [What it means - underlying needs, motivations, mental models]
**Implication:** [Product and design recommendations]
**Confidence:** [High/Medium/Low, with reasoning]

### 2. [Insight Theme]
[Repeat structure]

## User Needs & Jobs-to-be-Done
- [Need 1]: [Description, context, priority signals]
- [Need 2]: [Description, context, priority signals]

## Pain Points & Friction
- [Pain point 1]: [Description, severity, frequency, workarounds]
- [Pain point 2]: [Description, severity, frequency, workarounds]

## Behavioral Patterns
- [Pattern 1]: [Description, implications]
- [Pattern 2]: [Description, implications]

## Mental Models & Expectations
[How users think about the problem space, what they expect from solutions]

## Edge Cases & Contradictions
[Outlier behaviors, conflicting needs, unresolved tensions]

## Opportunities & Recommendations

### High Priority
1. [Opportunity]: [Rationale, impact potential]

### Medium Priority
2. [Opportunity]: [Rationale, impact potential]

### Exploratory
3. [Opportunity]: [Rationale, risks, unknowns]

## Risks & Constraints
[Market, regulatory, technical, or user adoption risks surfaced in research]

## Open Questions
[Areas requiring further research or validation]
Quality Standards
What Good Analysis Looks Like
✅ Interpretation over repetition

"Users struggle to trust the system because they've been burned by unreliable software in past roles"
Not: "User said they don't trust it"

✅ Patterns and evidence

"4 of 5 administrators mentioned manually cross-checking data in spreadsheets, suggesting systematic trust issues with system accuracy"

✅ Contextual understanding

"In Germany, childcare centers must comply with KitaG documentation requirements, which explains the emphasis on audit trails and signature workflows"

✅ Actionable implications

"Consider making data provenance visible at the field level, allowing users to verify information source and update history"

✅ Nuance and confidence

"This pattern emerged strongly among experienced users (5+ years) but was less pronounced among recent hires, suggesting it may be learned behavior rather than intuitive expectation"

What to Avoid
❌ Verbatim transcript summaries

"The user talked about calendars and then mentioned events"

❌ Generic insights

"Users want the system to be easy to use"

❌ Assumptions presented as facts

"Users need a mobile app" (without evidence)

❌ Design solutions in insights section

Reserve specific UI recommendations for opportunities section

❌ Overlooking contradictions

Acknowledge when users say conflicting things

Advanced Analysis Techniques
Behavioral Archaeology
Look beyond what users say they do to what they actually do:

Workarounds reveal unmet needs
Manual processes indicate automation opportunities
External tools signal feature gaps

Jobs-to-be-Done Framing
What is the user hiring this product to do?

Functional job (task completion)
Emotional job (how they want to feel)
Social job (how they want to be perceived)

Constraint Mapping
Identify what limits user behavior:

Technical constraints
Organizational policies
Regulatory requirements
Cultural norms
Cognitive load

Motivation Spectrum
Map users across:

High motivation / High ability (power users)
High motivation / Low ability (need guidance)
Low motivation / High ability (efficiency seekers)
Low motivation / Low ability (need simplification)

Customization Options
When invoking this skill, you can request:
Focus Areas

"Focus on workflow efficiency pain points"
"Emphasize trust and security themes"
"Highlight onboarding and learning curve insights"

Output Format

"Provide a concise 1-page executive summary"
"Create detailed findings with evidence quotes"
"Organize by user persona/role"
"Prioritize by impact vs. effort"

Comparison Analysis

"Compare findings across junior vs. senior user segments"
"Highlight differences between German and Italian users"
"Contrast mobile vs. desktop behavior patterns"

Confidence Calibration

"Flag all assumptions and note evidence quality"
"Indicate which findings need validation"
"Distinguish between strong patterns and weak signals"

Integration with Other Skills
This skill works well in combination with:

Product strategy: Translate research into roadmap priorities
Design systems: Inform component and pattern decisions
Documentation: Create research repositories and insight libraries
Competitive analysis: Contextualize findings against market alternatives

Example Use Cases
Use Case 1: Post-Interview Analysis
Input: 5 user interview transcripts from German childcare administrators
Output: Research findings report identifying calendar management pain points, trust issues with automated notifications, and opportunities for compliance-oriented audit features
Use Case 2: Cross-Market Comparison
Input: Interview data from Germany and Italy for the same product
Output: Comparative analysis highlighting cultural differences in feature priorities, communication norms, and regulatory expectations
Use Case 3: Feature Validation
Input: Interviews focused on specific proposed feature
Output: Validation report assessing user need strength, usability concerns, competitive context, and implementation considerations
Use Case 4: Persona Refinement
Input: Broad user research across multiple roles
Output: Behavioral patterns, needs, and mental models organized by user type to inform persona documentation
Quality Checklist
Before finalizing research findings, verify:

 Insights go beyond surface observations
 Findings are supported by specific evidence
 Patterns are identified across multiple users
 Contradictions and edge cases are acknowledged
 Domain and market context is integrated
 Product implications are clear and actionable
 Confidence levels are calibrated appropriately
 Language is professional and stakeholder-appropriate
 Structure enables quick scanning and deep reading
 Recommendations are prioritized and feasible
