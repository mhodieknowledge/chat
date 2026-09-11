# AFRICAN BUILDER OPPORTUNITY & COLLABORATION PLATFORM
# PRODUCT DISCOVERY, BRAINSTORMING & SYSTEM PLANNING BRIEF

You are the PRODUCT STRATEGIST, PRODUCT ARCHITECT, UX STRATEGIST, SYSTEM PLANNER, RESEARCHER, AND TECHNICAL PLANNING AGENT for this project.

IMPORTANT:

You are NOT the final coding agent for this stage.

Your job is to deeply understand the product vision below, challenge it where necessary, brainstorm missing ideas, research where appropriate, design the complete product concept, determine how the systems should work together, and then produce a comprehensive implementation/design specification that another coding agent can follow.

The final coding agent will receive the planning artifacts you create.

Therefore, do NOT produce a shallow product plan.

Think through the product as if you were preparing a serious production system for another highly capable agent to implement.

You should be ambitious.

Do NOT artificially limit the product because it may be complex.

Do NOT say "this is too much for an MVP" and remove major functionality simply to make the planning easier.

The purpose of this stage is to understand and plan the COMPLETE product.

After the planning is complete, produce the necessary markdown/text specification files that can be handed directly to the coding agent.

The coding agent should be able to read your output and understand:

- What the product is
- Who it is for
- What every major feature does
- How users move through the product
- How systems interact
- What data exists
- How AI is used
- How opportunity discovery works
- How collaboration works
- How teams work
- How projects work
- How moderation works
- How the admin system works
- How the UI should behave
- What the design language should be
- What technical architecture is appropriate
- What services should be used
- What services should NOT be used
- How to operate within a $0/month constraint
- How everything should be implemented

The second agent should NOT have to rediscover the product concept.

Your output should become the source of truth for implementation.

---

# 1. CORE PRODUCT CONCEPT

The original idea is an Africa-focused website that discovers upcoming hackathons and displays them.

However, that is NOT sufficient.

A simple hackathon aggregator is not the intended product.

The larger vision is:

AN AFRICA-FOCUSED BUILDER OPPORTUNITY AND COLLABORATION PLATFORM.

The platform should help African builders:

DISCOVER opportunities.

DISCOVER people.

FIND collaborators.

PROPOSE projects.

JOIN projects.

FORM TEAMS.

BUILD projects.

COMPETE in hackathons and competitions.

LEARN about programs and resources.

USE AI to make better decisions.

The fundamental loop is:

DISCOVER → CONNECT → BUILD → COMPETE → GROW

The platform should answer a much bigger question than:

"What hackathons are happening?"

It should answer:

"What can I do next, who can I do it with, and what can we build?"

---

# 2. AFRICA-FIRST

The platform must be genuinely Africa-focused.

Do not simply create a generic global opportunities website and add an "Africa" filter.

The ecosystem should prioritize:

- African opportunities
- Opportunities organized by African organizations
- Opportunities open specifically to Africans
- Country-specific African opportunities
- Regional African opportunities
- Africa-wide opportunities
- Global opportunities where Africans are eligible
- Remote opportunities realistically accessible from Africa
- African developer programs
- African startup programs
- African innovation ecosystems
- African education opportunities
- African technology communities

The system should understand that Africa is not one country.

Countries should be represented individually.

Examples include:

Zimbabwe
South Africa
Zambia
Botswana
Kenya
Nigeria
Ghana
Rwanda
Uganda
Tanzania
Egypt
Ethiopia
Morocco
Namibia
Malawi
Mozambique
and other African countries.

Opportunities should be able to specify:

- Country
- Multiple countries
- Region
- Africa-wide
- Global
- Remote
- In-person
- Hybrid

---

# 3. DO NOT LIMIT IT TO HACKATHONS

Hackathons are an important category, but they are only one part of the ecosystem.

The platform should support opportunities such as:

- Hackathons
- Coding competitions
- AI challenges
- Data competitions
- Innovation challenges
- Startup competitions
- Pitch competitions
- Grants
- Fellowships
- Scholarships
- Internships
- Accelerators
- Bootcamps
- Developer programs
- Research opportunities
- Open-source programs
- Entrepreneurship programs
- Community challenges
- Technology programs
- Other relevant opportunities

The system must be extensible so additional opportunity types can be introduced later.

---

# 4. AFRICAN PLATFORMS AND ORGANIZATIONS

The platform should also help users discover established African ecosystems.

Examples may include:

- ALX
- African Leadership University
- African developer communities
- African startup ecosystems
- African innovation hubs
- University innovation programs
- African technology organizations
- African coding initiatives
- Developer communities
- Entrepreneurship ecosystems

The purpose is NOT to compete with these platforms.

The platform acts as a discovery layer.

For example:

A person may not know ALX has a particular program.

They discover it here.

A student may not know that a university is running an innovation challenge.

They discover it here.

A developer may not know that an international competition accepts participants from Zimbabwe.

They discover it here.

The platform should make the fragmented opportunity ecosystem easier to navigate.

---

# 5. THE THREE CORE WORLDS

The platform should fundamentally revolve around three connected concepts:

## OPPORTUNITIES

Things people can apply for, join, participate in, or pursue.

Examples:

Hackathons
Competitions
Grants
Fellowships
Programs
Challenges
Scholarships
etc.

## PEOPLE

African builders who want to:

- Build
- Collaborate
- Find teams
- Join projects
- Participate in opportunities

## PROJECTS

Things people are building or want to build.

Examples:

- Startup ideas
- Hackathon projects
- Open-source projects
- Student projects
- Research projects
- Community projects
- AI experiments
- Side projects

These three worlds must be interconnected.

OPPORTUNITY → PEOPLE

OPPORTUNITY → PROJECT

PEOPLE → PROJECT

PROJECT → OPPORTUNITY

PEOPLE → OPPORTUNITY

This interconnected model is one of the most important aspects of the product.

---

# 6. OPPORTUNITY DIRECTORY

Design a complete opportunity discovery system.

Each opportunity should ideally contain structured information such as:

- Name
- Organization
- Organization profile
- Description
- Category
- Subcategory
- Country
- Region
- Eligibility
- Deadline
- Start date
- End date
- Online / physical / hybrid
- Individual / team
- Team size
- Prize
- Currency
- Funding
- Skills
- Technologies
- Industry
- Experience level
- Student eligibility
- Age requirements
- Cost
- Requirements
- Application process
- Official source
- Official application link
- Source URL
- Verification state
- Last checked
- Status
- Tags

Do not simply copy raw website text into the interface.

The information should be normalized and presented clearly.

---

# 7. OPPORTUNITY DISCOVERY

Users should be able to browse and filter opportunities.

Potential filters include:

- Country
- Region
- Category
- Industry
- Technology
- Remote
- In-person
- Hybrid
- Individual
- Team
- Beginner
- Intermediate
- Advanced
- Student
- Free
- Paid
- Prize
- Deadline
- Organization

Deadline filters should include useful states such as:

- Closing today
- Closing soon
- Closing this week
- Closing this month
- Upcoming

Think carefully about the UX of this discovery experience.

---

# 8. NATURAL LANGUAGE SEARCH

Search should not be limited to exact keyword matching.

Users should be able to type natural requests such as:

"Remote AI hackathons open to people in Zimbabwe."

"Agriculture competitions closing this month."

"Free AI programs for African students."

"Frontend developers looking for hackathon teams."

"People in Kenya building climate projects."

"Opportunities for beginners in Python."

The platform should interpret intent and return useful results.

AI-assisted search must never invent opportunities.

---

# 9. AI OPPORTUNITY MATCHING

AI should be a genuine product capability.

Do NOT simply add a chatbot.

AI should analyze user information and opportunity information to produce meaningful recommendations.

Example:

User:

"I am a university student from Zimbabwe. I know Python and JavaScript. I'm interested in AI and agriculture. I have three weeks available and prefer remote opportunities."

The system could recommend:

Agriculture AI Challenge — 94% match

Why:

- Zimbabwe eligible
- Africa-wide
- Remote
- AI relevant
- Agriculture relevant
- Python useful
- Timeline compatible

The recommendation system should explain why.

Determine how the matching logic should work.

Determine which parts should be deterministic rules and which parts should use AI.

---

# 10. AI ELIGIBILITY ANALYSIS

Users should be able to ask:

"Can I apply?"

The system should inspect the opportunity's eligibility information.

Example:

LIKELY ELIGIBLE

Country: ✓
Student requirement: ✓
Age: ✓
Skills: ✓
Team requirement: Team of 3–5
Deadline: September 30

The system must distinguish:

- Confirmed
- Likely
- Unclear
- Not eligible

Never fabricate eligibility.

If the source is ambiguous, explicitly state that.

---

# 11. PERSONALIZED OPPORTUNITY FEED

Profiles should make the platform increasingly personalized.

Relevant signals may include:

- Country
- Skills
- Technologies
- Interests
- Experience
- Student status
- Preferred categories
- Preferred format
- Collaboration preferences
- Saved opportunities
- Joined opportunities
- Previous projects
- Previous participation

The feed should prioritize relevance.

Do not optimize for meaningless engagement.

---

# 12. "WHAT SHOULD I DO NEXT?"

Design a powerful experience around:

"WHAT SHOULD I DO NEXT?"

A user should be able to ask the platform what opportunities or actions make sense for them.

For example:

THIS WEEK

1. Apply to an AI challenge closing in 5 days.
2. Join a team for an upcoming hackathon.
3. Consider a free developer program.
4. Join an open-source project.
5. Continue developing your current project.

The platform should turn information into actionable recommendations.

---

# 13. PROJECT BOARD

Users must be able to publicly propose projects.

Example:

PROJECT:
Crop Disease AI

PROBLEM:
Smallholder farmers struggle to identify crop diseases early.

SOLUTION:
An AI system that helps identify crop diseases from images.

LOOKING FOR:

- Machine learning developer
- Mobile developer
- UI/UX designer

SKILLS:

Python
AI/ML
React Native
Agriculture

STATUS:

Looking for collaborators

Project pages should feel like serious project listings, not social posts.

---

# 14. PROJECT LIFECYCLE

Projects should have states such as:

- Idea
- Looking for collaborators
- Team forming
- Building
- Testing
- Completed
- Archived

Consider whether additional states are useful.

Think through:

- Ownership
- Contributors
- Roles
- Project activity
- Milestones
- External repositories
- Demo links
- Documentation
- Opportunities connected to the project

---

# 15. PROJECT COLLABORATION

Users should be able to express interest in a project.

For example:

"I'm interested"

Then indicate:

"I can help with frontend."

The project owner can review requests and decide whether to connect.

Think carefully about:

- Privacy
- Spam
- Communication
- Requests
- Approvals
- Rejections
- Blocking
- Reporting
- Notifications

---

# 16. HACKATHON TEAM FORMATION

A user viewing a hackathon should have an obvious path to:

FIND TEAMMATES

Users should be able to indicate:

- Hackathon
- Role needed
- Role offered
- Skills
- Experience
- Country
- Availability
- Interests

Potential roles:

- Team lead
- Frontend
- Backend
- AI/ML
- Data
- Mobile
- UI/UX
- Product
- Business
- Pitching
- Research
- Other

Design a complete team formation workflow.

---

# 17. AI TEAM MATCHING

AI should help identify complementary collaborators.

Example:

Person A:
Python + AI + Agriculture

Person B:
React + UI/UX + Agriculture

Person C:
Business + Pitching + Startups

The platform may identify them as a potentially complementary team.

It should explain:

"Your skills complement each other and you share an interest in AgriTech."

Do not claim that compatibility is guaranteed.

---

# 18. PROJECT → OPPORTUNITY MATCHING

When someone creates a project, AI should identify relevant opportunities.

Example:

Project:

"AI platform for farmers."

Potential recommendations:

- AgriTech hackathons
- AI competitions
- Climate competitions
- Agriculture startup competitions
- Grants
- Innovation programs

This should be an actual relationship in the system.

---

# 19. OPPORTUNITY → PROJECT MATCHING

When someone views a hackathon, show relevant:

- Existing projects
- Project ideas
- Builders
- People looking for teammates
- Teams forming

This makes opportunity pages much more useful.

---

# 20. AI PROJECT IDEA GENERATOR

Users should be able to request ideas for a particular opportunity.

Example:

"Give me project ideas for this hackathon."

AI should understand:

- Challenge
- Judging criteria
- Theme
- Constraints
- Team size
- Time available

Ideas should be relevant to African realities where appropriate.

Possible output:

- Problem
- Solution
- Target users
- Features
- Differentiation
- MVP
- Impact
- Feasibility
- Technology direction

Avoid generic ideas.

---

# 21. AI HACKATHON COPILOT

For participating teams, AI can assist with:

- Understanding the challenge
- Brainstorming
- Idea validation
- MVP definition
- Task breakdown
- Team role assignment
- Project description
- README
- Pitch
- Presentation
- Demo script
- Weakness analysis

The AI should act as a strategic copilot.

---

# 22. AI JUDGING SIMULATOR

If judging criteria are available, users should be able to submit their project for simulated evaluation.

Example:

Innovation: 8/10
Impact: 7/10
Technical implementation: 8/10
Presentation: 6/10
Feasibility: 8/10

Then explain:

BIGGEST WEAKNESS:

The project has strong technical implementation, but its impact is not clearly demonstrated.

RECOMMENDATION:

Quantify expected outcomes and explain how the solution works for the intended users.

Clearly label this as an AI simulation/review, not official judging.

---

# 23. BUILDER PROFILES

Profiles should focus on building.

Potential information:

- Name
- Country
- Bio
- Skills
- Technologies
- Interests
- Experience
- Projects
- Contributions
- Achievements
- Portfolio
- GitHub
- Other relevant links
- Collaboration interests
- Availability

The profile should communicate:

"This is what I build."

Not:

"This is my generic social media profile."

---

# 24. BUILDER DISCOVERY

Users should be able to discover:

- AI developers
- Frontend developers
- Backend developers
- Designers
- Data scientists
- Researchers
- Product people
- Entrepreneurs
- Students
- People looking for teammates
- People interested in specific industries

Examples:

"AI developers in Africa"

"Frontend developers looking for hackathon teams"

"People interested in AgriTech"

"Builders in Zimbabwe"

"People looking for collaborators"

---

# 25. COMMUNITY PHILOSOPHY

Do NOT turn this into another social network.

Avoid unnecessary:

- Endless feeds
- Likes everywhere
- Follower obsession
- Engagement bait
- Random posting
- Generic social content

Community should revolve around:

- Opportunities
- Projects
- Collaboration
- Teams
- Building
- Learning
- Achievements

Every social feature must serve the product mission.

---

# 26. OPPORTUNITY DATA COLLECTION

The platform needs a way to discover opportunities.

Research realistic methods using:

- Public APIs
- RSS
- Public event feeds
- Official websites
- Public pages
- Public datasets
- Official organization pages
- Other legally accessible sources

Do not blindly scrape the internet.

Think through:

- Terms of use
- Robots rules
- Rate limits
- Source reliability
- Duplicate detection
- Expiration
- Changes
- Attribution
- Data freshness

Design an ingestion system that can evolve.

---

# 27. AUTOMATIC STRUCTURING

Opportunity information may be unstructured.

The platform should transform it into structured records.

Example:

"Open to students and young developers across Africa. Teams of 2–5. Applications close September 30."

Should become:

Region: Africa
Eligibility: Students / young developers
Team size: 2–5
Deadline: September 30

AI can assist where appropriate.

Think carefully about confidence and human/admin review.

---

# 28. DATA QUALITY

The system should identify:

- Duplicates
- Expired opportunities
- Changed deadlines
- Broken URLs
- Missing fields
- Conflicting information
- Low-confidence extraction
- Duplicate organizations

Important data should retain source attribution and timestamps.

---

# 29. ORGANIZATION PAGES

Organizations should be represented as first-class entities where useful.

An organization can have:

- Name
- Description
- Country
- Region
- Website
- Verification
- Categories
- Opportunities
- Programs

This makes the ecosystem easier to explore.

---

# 30. DEADLINES

Deadlines are extremely important.

Show:

- Closing today
- Closing in 2 days
- Closing this week
- Closing this month
- Future

Users should be able to save opportunities.

Consider reminders.

Do not make notifications spammy.

---

# 31. OPPORTUNITY TRACKING

Users should be able to track:

- Saved
- Planning to apply
- Applied
- Joined
- Participating
- Completed
- Won

Design the complete personal opportunity tracker.

---

# 32. ACHIEVEMENTS

Users may build meaningful participation records:

- Hackathon participant
- Finalist
- Winner
- Project creator
- Open-source contributor
- Team contributor
- Competition participant

Avoid meaningless gamification.

---

# 33. AFRICA MAP / DISCOVERY

Consider an Africa-centric discovery experience.

Users could explore:

- Opportunities
- Builders
- Projects
- Organizations

by country.

The map must provide actual utility.

Do not create a decorative map just because Africa is part of the branding.

---

# 34. HOMEPAGE

The homepage should immediately communicate:

DISCOVER OPPORTUNITIES.
FIND PEOPLE.
BUILD PROJECTS.

Potential primary actions:

FIND AN OPPORTUNITY

FIND A PROJECT

FIND COLLABORATORS

START A PROJECT

The exact copy should be refined during design.

---

# 35. USER JOURNEY — OPPORTUNITY FIRST

Example:

A Zimbabwean university student arrives.

They identify themselves as:

Developer
AI interested
Beginner/intermediate

They discover a remote AI hackathon.

They click:

FIND TEAMMATES

The platform recommends compatible builders.

They form a team.

They create a project.

AI helps refine it.

The platform recommends another competition.

The team uses the judging simulator.

They improve the project.

They submit.

The project becomes part of their builder profile.

---

# 36. USER JOURNEY — PROJECT FIRST

Another person arrives with:

"I want to build an open-source African public transport data platform."

They publish the project.

The platform helps find:

- Data engineers
- Backend developers
- GIS developers
- Designers

AI recommends:

- Grants
- Hackathons
- Open-source programs
- Innovation challenges

The project becomes a collaboration hub.

---

# 37. USER JOURNEY — NO IDEA

Someone discovers a hackathon but has no idea what to build.

The platform helps them:

- Understand the challenge
- Find teammates
- Generate ideas
- Compare ideas
- Evaluate ideas
- Find relevant existing projects
- Plan an MVP

---

# 38. USER JOURNEY — "WHAT SHOULD I DO?"

A user simply says:

"I want to improve my skills and build something."

The platform should help them discover:

- Learning opportunities
- Projects
- Competitions
- Teams
- Programs

This is the broader vision.

---

# 39. TRUST AND VERIFICATION

Opportunity information can become outdated.

Use concepts such as:

- Verified
- Official source
- Recently checked
- Community reported
- Potentially outdated
- Expired

Users should be able to report:

- Expired opportunity
- Incorrect deadline
- Incorrect eligibility
- Broken link
- Scam
- Duplicate
- Incorrect information

Think through verification workflows.

---

# 40. USER-GENERATED CONTENT MODERATION

Projects, profiles and collaboration posts require moderation.

Plan for:

- Spam
- Fake profiles
- Fake projects
- Scam links
- Harassment
- Impersonation
- Abuse
- Malicious content
- Inappropriate content
- Suspicious organizations

Include:

- Reporting
- Blocking
- Admin review
- Automated detection where useful
- Rate limits
- Account restrictions

---

# 41. PRIVACY

Users may have personal information and contact mechanisms.

Think carefully about:

- Public vs private profile fields
- Contact information
- Messaging
- Blocking
- Account deletion
- Data deletion
- Visibility settings
- Public project information

Do not expose personal information unnecessarily.

---

# 42. FREE-FIRST REQUIREMENT

THIS IS A HARD CONSTRAINT.

The initial product should operate using **genuinely free services wherever realistically possible.**

Target:

# $0/MONTH

for the initial production system if realistically achievable.

Do NOT assume there is a paid API budget.

Do NOT design around expensive infrastructure.

Do NOT rely on a "free trial" and call it free.

For every external service you consider, evaluate:

1. Is it genuinely free?
2. Does it require a credit card?
3. What are the limits?
4. Is there a usage cap?
5. Can the system operate without it?
6. Is there an open-source alternative?
7. Can usage unexpectedly create charges?
8. What happens when the quota is exhausted?
9. Is it appropriate for a public production project?

Prefer:

- Open source
- Free tiers
- Public APIs
- Public datasets
- Self-hosting where practical
- Free hosting
- Free databases
- Free authentication
- Free storage
- Free email where practical
- Free monitoring
- Free developer tools

For AI, investigate:

- Genuine free API tiers
- Open-source models
- Local inference
- Self-hosted inference where practical
- Free inference providers
- Hybrid approaches
- Deterministic algorithms where AI is unnecessary

Do NOT make AI dependent on an expensive paid API if a realistic free architecture exists.

Also design graceful fallbacks for unavailable AI services.

---

# 43. NO ARTIFICIAL FEATURE LIMITATION

Do not interpret the $0 requirement as a reason to remove major functionality.

Instead, find intelligent ways to implement functionality within the constraint.

If a feature requires an external service that is not free, investigate:

- Open-source alternatives
- Free alternatives
- Client-side processing
- Cached data
- Deterministic logic
- Smaller models
- Self-hosting
- Hybrid architecture

If something genuinely cannot be done for $0, document the limitation clearly and design the product so it can operate without that paid dependency.

---

# 44. FULL PRODUCT EXPECTATION

You are planning a complete product.

Do NOT respond with:

"Start with a simple MVP and maybe add collaboration later."

The complete vision matters.

You should plan the full ecosystem.

You may identify phases for implementation order, but do NOT remove major systems from the architecture simply because they are ambitious.

The coding agent is capable of building a large system.

Your job is to give it a complete blueprint.

---

# 45. ADMIN SYSTEM

Plan a serious administrative system.

Potential capabilities:

- Opportunity management
- Organization management
- Data source management
- Verification
- Expired opportunity management
- Duplicate management
- User moderation
- Project moderation
- Reports
- User management
- Categories
- Tags
- AI extraction review
- AI confidence review
- Data ingestion monitoring
- System health
- Analytics

The admin system is part of the product.

---

# 46. ANALYTICS

Think through useful analytics for the platform.

Examples:

- Opportunity views
- Saves
- Applications tracked
- Team formation
- Project creation
- Collaboration requests
- Search queries
- Popular categories
- Country activity
- Opportunity conversion
- Project activity

Analytics should help improve the platform rather than simply create vanity metrics.

---

# 47. NOTIFICATIONS

Think through useful notifications:

- Opportunity deadline approaching
- Collaboration request
- Team invitation
- Project interest
- New recommended opportunity
- Project update
- Application reminder
- Team activity

Avoid notification spam.

---

# 48. SEARCH AND DISCOVERY RELATIONSHIPS

Search should understand entities.

A user may search for:

- An opportunity
- Organization
- Person
- Project
- Skill
- Country
- Category

Search should be designed around the interconnected ecosystem.

---

# 49. MOBILE-FIRST

The platform must work extremely well on:

- Phones
- Tablets
- Laptops
- Desktop

Assume many African users will primarily access it through mobile devices.

Do not simply shrink a desktop interface.

Design mobile experiences deliberately.

---

# 50. DESIGN QUALITY

This must feel like a serious technology product.

Avoid:

- Generic AI dashboard aesthetic
- Generic SaaS templates
- Excessive gradients
- Fake statistics
- Fake community activity
- Empty decorative UI
- Chatbot-first interfaces
- Unnecessary gamification
- Social-media clutter
- AI-generated filler

Prioritize:

- Strong typography
- Excellent hierarchy
- Clear navigation
- High-quality cards
- Strong opportunity pages
- Strong project pages
- Strong profiles
- Excellent search
- Useful filters
- Excellent mobile UI
- Accessibility
- Clear trust signals
- Useful empty states
- Good loading states
- Good error handling
- Fast workflows

The platform should look credible enough for serious African developers, students, founders, researchers and professionals.

---

# 51. BRANDING

The final brand should not sound like:

"Africa Hackathon Finder 3000"

Avoid overly generic names.

The brand should be able to grow beyond hackathons.

The conceptual territory includes:

- Building
- Opportunity
- Collaboration
- Purpose
- Growth
- African innovation
- Community
- Discovery

Potential naming directions may include African words relating to:

- Build
- Create
- Opportunity
- Together
- Purpose
- Work
- Growth

But do proper naming research before settling on a name.

Check:

- Existing companies
- Existing apps
- Existing platforms
- Domain availability
- Social handles where relevant
- Trademark/brand conflicts where practical

Do not become attached to an unavailable name.

---

# 52. PRODUCT DIFFERENTIATION

The product must answer:

WHY DOES THIS NEED TO EXIST?

Because African opportunities are fragmented.

A person may need to visit many websites to discover:

- Hackathons
- Grants
- Fellowships
- Developer programs
- Competitions
- Projects
- Collaborators

Even after finding an opportunity, they may not have a team.

Even after finding a team, they may not know what to build.

Even after choosing a project, they may not know whether it fits a competition.

The platform connects these problems.

The core value is:

NOT:

"Here are some opportunities."

BUT:

"Here is what you can do, who you can do it with, and how you can get started."

---

# 53. THE CORE LOOP

Everything should reinforce:

I DISCOVER AN OPPORTUNITY.

↓

I UNDERSTAND WHETHER I AM ELIGIBLE.

↓

I FIND PEOPLE.

↓

WE FORM A TEAM.

↓

WE CREATE OR JOIN A PROJECT.

↓

AI HELPS US PLAN AND IMPROVE.

↓

WE BUILD.

↓

WE COMPETE / LAUNCH / CONTRIBUTE.

↓

THE PROJECT AND EXPERIENCE BECOME PART OF OUR PROFILE.

↓

THE PLATFORM FINDS OUR NEXT OPPORTUNITY.

This is the product.

---

# 54. YOUR FIRST RESPONSIBILITY: BRAINSTORM

Before producing the final implementation specification:

Think deeply about the concept.

Identify:

- Missing features
- Weaknesses
- Opportunities
- Risks
- User problems
- Product loops
- Potential network effects
- Ways to make collaboration stronger
- Ways to make AI genuinely useful
- Ways to make the Africa focus meaningful
- Ways to avoid becoming a generic social network
- Ways to avoid becoming a basic directory

Challenge assumptions.

If a proposed feature is weak, improve it.

If an important feature is missing, add it.

Do not blindly follow the brief.

The brief describes the vision; you are responsible for turning it into a strong product.

---

# 55. THEN DESIGN THE COMPLETE SYSTEM

After brainstorming, determine the complete product architecture.

You should plan:

## Product architecture

All major product areas.

## User architecture

User roles, permissions and account states.

## Opportunity architecture

How opportunities are represented and connected.

## Project architecture

How projects work and evolve.

## Team architecture

How teams form and operate.

## Collaboration architecture

How people connect.

## Organization architecture

How organizations are represented.

## AI architecture

Every AI workflow and why it exists.

## Recommendation architecture

How matching works.

## Search architecture

How discovery works.

## Data ingestion architecture

How opportunities are collected and updated.

## Moderation architecture

How abuse is handled.

## Admin architecture

How the platform is operated.

## Notification architecture

How users are informed.

## Analytics architecture

What should be measured.

---

# 56. UX SPECIFICATION

Create detailed UX specifications.

For every major area, define:

- Purpose
- User goal
- Entry points
- Main screen
- Components
- Actions
- States
- Empty states
- Loading states
- Error states
- Success states
- Mobile behavior
- Desktop behavior
- Navigation
- Related screens

Do not merely list screen names.

Describe the actual experience.

---

# 57. DESIGN SYSTEM

Create a complete design system specification that the coding agent can implement.

Define:

- Design principles
- Typography
- Type scale
- Spacing
- Grid
- Layout
- Color system
- Surface hierarchy
- Borders
- Radius
- Shadows
- Cards
- Buttons
- Inputs
- Selects
- Filters
- Tabs
- Navigation
- Tables
- Lists
- Badges
- Status indicators
- Modals
- Drawers
- Toasts
- Tooltips
- Empty states
- Loading states
- Skeletons
- Charts
- Maps
- AI interfaces
- Opportunity cards
- Project cards
- Builder cards
- Organization cards

The design system must be coherent.

Avoid generic component-library output.

---

# 58. RESPONSIVE DESIGN SYSTEM

Explicitly define how important components behave across:

- Small mobile
- Large mobile
- Tablet
- Laptop
- Desktop
- Wide desktop

Do not rely on "make it responsive."

Define the actual behavior.

---

# 59. ACCESSIBILITY

Plan accessibility from the beginning.

Include:

- Keyboard navigation
- Focus states
- Screen reader support
- Contrast
- Semantic structure
- Form labels
- Error messaging
- Touch target sizes
- Reduced motion
- Accessible tables
- Accessible dialogs
- Accessible notifications

---

# 60. TECHNICAL PLANNING

After the product and UX are understood, choose an appropriate technical architecture.

Determine:

- Frontend
- Backend
- Database
- Authentication
- Search
- AI
- Storage
- Data ingestion
- Scheduled jobs
- Notifications
- Analytics
- Admin
- Security
- Hosting
- Monitoring

Do not select technology based purely on popularity.

Optimize for:

- Reliability
- Simplicity
- Maintainability
- Free operation
- Performance
- Security
- Developer productivity
- Ability to scale later

---

# 61. FREE INFRASTRUCTURE RESEARCH

Research current free options before recommending services.

Free tiers and policies change.

Verify current limits where possible.

For each external service provide:

SERVICE
PURPOSE
FREE LIMIT
CREDIT CARD REQUIRED?
RISKS
FALLBACK
WHY IT WAS SELECTED

Do this for all major dependencies.

The final implementation should not unexpectedly incur charges.

---

# 62. AI COST STRATEGY

AI is important, but AI calls can become expensive.

Design intelligent approaches such as:

- Caching
- Pre-computation
- Embeddings where free
- Deterministic filtering before AI
- Small models for simple tasks
- Larger models only where necessary
- Local/open-source models
- User-triggered expensive operations
- Rate limits
- Request quotas
- Fallbacks

Do not send every search request to an expensive model.

AI should be used where it provides actual value.

---

# 63. SECURITY

Plan:

- Authentication
- Authorization
- Sessions
- Password/security strategy if applicable
- OAuth if applicable
- API security
- Rate limiting
- Abuse prevention
- Admin security
- Secrets
- Input validation
- File security
- URL safety
- Data privacy
- Account deletion

---

# 64. PERFORMANCE

Think through:

- Page performance
- Search performance
- Opportunity ingestion
- AI latency
- Caching
- Database queries
- Image optimization
- Mobile performance
- Background processing

The platform should feel fast.

---

# 65. SEO AND DISCOVERABILITY

Opportunity pages and public project pages should be discoverable through search engines where appropriate.

Think through:

- Metadata
- Open Graph
- Structured data
- Indexability
- Canonical URLs
- Public/private pages
- Sitemap
- Robots
- Dynamic metadata

Do not expose private user data through search engines.

---

# 66. CONTENT STRATEGY

The platform will need meaningful initial content.

Do not fill it with fake users or fake activity.

Think about:

- Seed opportunities
- Real organizations
- Public opportunities
- Example projects clearly marked as examples if needed
- Empty states
- Onboarding

Never present fabricated statistics as real.

---

# 67. DOCUMENTATION TO PRODUCE

After brainstorming and planning, create the implementation artifacts.

At minimum, produce documents equivalent to:

1. PRODUCT_SPEC.md
2. SYSTEM_ARCHITECTURE.md
3. DESIGN_SYSTEM.md
4. UX_FLOWS.md
5. DATA_MODEL.md
6. AI_SYSTEM.md
7. OPPORTUNITY_INGESTION.md
8. COLLABORATION_SYSTEM.md
9. MODERATION_AND_TRUST.md
10. ADMIN_SYSTEM.md
11. FREE_INFRASTRUCTURE.md
12. SECURITY.md
13. SEO.md
14. IMPLEMENTATION_PLAN.md

You may create additional documents if useful.

These documents should be detailed enough that the coding agent can use them directly.

---

# 68. IMPLEMENTATION PLAN

Create an implementation sequence.

It should identify dependencies between systems.

For example:

Foundation
↓

Authentication
↓

Core entities
↓

Opportunity system
↓

Projects
↓

Profiles
↓

Collaboration
↓

AI
↓

Recommendations
↓

Admin
↓

Data ingestion
↓

Polish
↓

Testing

However, do NOT blindly use this exact order.

Determine the best dependency-aware sequence yourself.

---

# 69. CODING AGENT HANDOFF

The final output must be designed for another agent.

The coding agent should be able to receive the documents and immediately understand:

"Here is exactly what I am building."

Avoid vague instructions such as:

"Make it modern."

Instead specify what modern means for this product.

Avoid:

"Add AI."

Instead specify:

"AI should perform opportunity matching, eligibility analysis, project-opportunity matching, team matching, project ideation, hackathon assistance and judging simulation, using the following workflows..."

Avoid:

"Make the UI responsive."

Instead specify the responsive behavior.

The goal is to eliminate ambiguity.

---

# 70. IMPORTANT: DO NOT CODE YET

At this stage your responsibility is to:

1. Brainstorm
2. Research
3. Challenge the concept
4. Define the product
5. Define the systems
6. Define the UX
7. Define the design system
8. Define the architecture
9. Define the data model
10. Define AI workflows
11. Define integrations
12. Define free infrastructure
13. Define security
14. Define moderation
15. Define admin
16. Produce implementation-ready documentation

Only after the planning artifacts are complete should a separate coding agent use them to implement the platform.

The output of this stage should be a **complete blueprint for the coding agent**.

---

# 71. FINAL PRODUCT TEST

Before finishing your planning, mentally test the complete product with at least these scenarios:

SCENARIO 1:
A Zimbabwean student looking for an AI hackathon.

SCENARIO 2:
A Kenyan developer looking for collaborators.

SCENARIO 3:
A Nigerian designer looking for a team.

SCENARIO 4:
A person with a project idea looking for developers.

SCENARIO 5:
A team looking for a hackathon that fits their existing project.

SCENARIO 6:
A user who has no idea what to build.

SCENARIO 7:
An organization wanting its opportunity discovered.

SCENARIO 8:
An admin discovering that an opportunity has expired.

SCENARIO 9:
A user reporting a suspicious opportunity.

SCENARIO 10:
A user returning to find their personalized recommendations.

Make sure the architecture supports all of these.

---

# 72. FINAL QUESTION

Throughout the entire process, keep asking:

> HOW DO WE MAKE IT DRAMATICALLY EASIER FOR AN AFRICAN BUILDER TO DISCOVER AN OPPORTUNITY, FIND THE RIGHT PEOPLE, START A PROJECT, AND ACTUALLY BUILD SOMETHING?

That is the product.

Not a hackathon directory.

Not a chatbot.

Not a social network.

Not a generic opportunity aggregator.

It is an interconnected African builder ecosystem where:

OPPORTUNITIES
+
PEOPLE
+
PROJECTS
+
AI
+
COLLABORATION

work together.

Now deeply brainstorm the product, identify improvements, research the necessary ecosystem and current free services, design the complete systems and user experience, and produce the comprehensive markdown/text planning artifacts that a separate coding agent can use as the source of truth for building the full platform.
