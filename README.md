# AI Marketing & Viral Video Studio

An AI-powered marketing and content production system built with Claude Code, designed to manage marketing strategy, social media content, video production, campaign planning, and performance analysis.

The goal is to create a unified AI marketing workflow that operates like a small digital marketing agency, combining specialised AI skills and agents to support multiple brands.

Initially designed for **Eazivo Business** and **Eazivo Family**, the system can be extended to other products and businesses.

## Overview

The AI Marketing & Viral Video Studio integrates specialised Claude Code skills for:

- Marketing strategy and campaign planning.
- Social media content creation and copywriting.
- Viral video storytelling and short-form production.
- Trend research and competitor analysis.
- SEO and conversion optimisation.
- Social media scheduling and publishing.
- Marketing analytics and content optimisation.

Instead of managing separate tools and workflows, the system coordinates marketing activities through a unified architecture, connecting research, content planning, production, approval, publishing, and analytics.

## Recommended Claude Code Skill Collections

### 1. Marketing Skills — Corey Haines

**Repository:** [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)

A comprehensive collection of marketing skills covering strategic planning, positioning, copywriting, social content, SEO, conversion optimisation, advertising, and product launches.

Particularly useful for SaaS products, mobile applications, and digital services.

**Key capabilities:**
- Product positioning and audience research.
- Marketing strategy and content planning.
- Social media copywriting.
- SEO and conversion optimisation.
- Campaign ideation and product launches.

**Cost:** Open source. External services may have separate costs.

### 2. Social Skills — Scrollmark

**Repository:** [scrollmark/social-skills](https://github.com/scrollmark/social-skills)

Focused on social media content strategy, attention-grabbing hooks, platform-specific storytelling, content repurposing, and performance analysis.

A complementary collection for creating engaging Instagram Reels, TikTok videos, Facebook posts, and other short-form content.

**Key capabilities:**
- Social media hooks and retention.
- Trend discovery and analysis.
- Platform-specific content optimisation.
- Short-form storytelling.
- Content repurposing.
- Post-performance evaluation.

**Cost:** Check repository licence and external integration requirements.

### 3. Marketing Skill — Marcos Modly

**Repository:** [marcosmodly/marketing-skill](https://github.com/marcosmodly/marketing-skill)

Marketing workflow resources for managing content creation, editorial calendars, competitive research, and campaign coordination.

**Potential capabilities:**
- Editorial planning.
- Competitor research.
- Short-form video scripting.
- Marketing workflow automation.
- Integration with external publishing services.

**Cost:** Repository resources may be free; integrations may require paid subscriptions.

### 4. Claude Marketing — Rebecca Rae

**Repository:** [thatrebeccarae/claude-marketing](https://github.com/thatrebeccarae/claude-marketing)

A collection focused on marketing execution, advertising workflows, campaign analysis, and performance optimisation.

**Key areas:**
- Meta advertising.
- TikTok advertising.
- Google Ads.
- Competitor analysis.
- Campaign evaluation.
- Marketing performance audits.

**Cost:** Skills and advertising-platform costs are separate.

### 5. AI Vita Skills

**Repository:** [ai-vita/skills](https://github.com/ai-vita/skills)

A collection of AI skills relevant to application marketing, acquisition, conversion, and retention.

**Key areas:**
- App Store Optimisation (ASO).
- Social media content.
- Customer research.
- Conversion analysis.
- Campaign strategy.
- User acquisition and retention.

**Cost:** Review the repository licence and any external service requirements.

> **Note:** Third-party skill availability, names, installation methods, and maintenance status may change. Verify the current repository structure and documentation before installation.

## Priority Skills

Rather than installing every available skill, the recommended approach is to start with a focused set of capabilities.

| Skill / Capability | Purpose |
|---|---|
| `product-marketing-context` | Understand the product, target audience, positioning, and value proposition. |
| `content-strategy` | Plan editorial calendars, content pillars, and campaigns. |
| `social-content` | Generate social media posts, captions, carousels, and platform-specific content. |
| Hook Analysis | Improve video openings and audience retention. |
| Trend Research | Identify relevant trends and content opportunities. |
| Ad Creative | Develop advertising concepts, scripts, and creative variations. |
| Content Performance Review | Analyse published content and identify opportunities for improvement. |
| Content Repurposing | Adapt existing content for multiple formats and platforms. |

Some capabilities may require custom skills or workflows rather than existing packages with these exact names.

## Installation

Install the selected skill collections using the Claude Code skills installer.

```bash
# Strategic marketing and content creation
npx skills add coreyhaines31/marketingskills -a claude-code

# Social media content and trends
npx skills add scrollmark/social-skills -a claude-code
```

The installer may allow individual skill selection.

Review repository contents, third-party scripts, permissions, and dependencies before installation.

Avoid installing overlapping skills that duplicate existing functionality.

## AI Agent Architecture

The studio uses specialised agents to coordinate the complete marketing workflow.

| Agent | Responsibility |
|---|---|
| **Marketing Director** | Coordinates marketing strategy, campaigns, brand positioning, and editorial calendars. |
| **Trend Researcher** | Researches emerging trends, competitors, audience discussions, and content opportunities. |
| **Content Strategist** | Develops content pillars, educational topics, storytelling concepts, and publishing plans. |
| **Content Creator** | Produces scripts, captions, carousels, social posts, and campaign copy. |
| **Video Studio** | Handles video editing, motion graphics, short-form production, and content repurposing. |
| **Analytics Specialist** | Evaluates performance metrics and recommends improvements. |
| **Social Media Manager** | Coordinates approved publishing schedules and platform-specific content distribution. |

All agents should share brand guidelines, campaign objectives, editorial calendars, and approval workflows.

## Unified Marketing Workflow

The system follows a connected marketing production process:

```text
Audience & Market Research
          |
          v
Marketing Strategy
          |
          v
Trend & Content Research
          |
          v
Content Planning
          |
          v
Scripts / Captions / Carousels
          |
          v
Video & Visual Production
          |
          v
Quality Review
          |
          v
Human Approval
          |
          v
Scheduling & Publishing
          |
          v
Analytics & Optimisation
          |
          +----> Future Content Planning
```

The workflow is designed to support both educational content and product-focused campaigns.

## Multi-Brand Support

The studio supports multiple brands while keeping their strategies and content independent.

### Eazivo Business

**Audience:** Australian sole traders and small service businesses.

**Content focus:**
- Small business management.
- Job scheduling and bookings.
- Shift and worker coordination.
- Customer communication.
- Productivity and operational efficiency.
- Service business growth.

### Eazivo Family

**Audience:** Parents and families looking to improve household organisation.

**Content focus:**
- Family scheduling.
- Household responsibilities.
- Children's chores and routines.
- Family communication.
- Parenting organisation.
- Practical educational content.

Each brand should maintain its own audience profiles, brand identity, tone of voice, messaging, campaigns, and publishing calendar.

## Social Media Management

AI skills provide instructions and processes that Claude can follow. However, accessing social media accounts, retrieving analytics, and publishing content requires external integrations or authorised APIs.

Potential integrations include:

- Instagram and Facebook.
- TikTok.
- Metricool.
- Analytics services.
- Content calendars and approval systems.

[Metricool](https://metricool.com/) is one possible integration for social media scheduling, calendar management, and analytics, subject to available API features and account permissions.

Publishing should remain subject to human approval.

## Automated Marketing Operations

A recurring marketing workflow can coordinate activities such as:

1. Research relevant trends and audience needs.
2. Identify potential educational and promotional content.
3. Generate content ideas and draft scripts.
4. Select suitable production formats.
5. Prepare videos, carousels, captions, and supporting assets.
6. Submit content for review and approval.
7. Schedule approved publications through connected services.
8. Analyse performance and use the findings to improve future content.

Automation requires an appropriate scheduler, configured integrations, and any necessary credentials.

The system should not publish content or initiate paid campaigns without explicit authorisation.

## Project Goals

The AI Marketing & Viral Video Studio aims to:

- Reduce repetitive marketing work.
- Improve content quality and consistency.
- Produce genuinely valuable educational content.
- Create engaging short-form videos and social media assets.
- Support multiple brands from one system.
- Maintain centralised editorial planning.
- Streamline content production and approval.
- Use audience insights and analytics to improve results.
- Scale marketing operations without requiring a large team.

## Future Development

Potential enhancements include:

- Automated content research and topic discovery.
- Community-driven audience research.
- Research-backed educational content creation.
- AI-generated carousel production.
- Advanced storytelling workflows.
- Brand-specific reusable templates.
- Cross-platform content repurposing.
- Integrated publishing queues.
- Analytics-driven recommendations.
- Automated marketing performance reports.

## Guiding Principle

**Create content that delivers genuine value before asking the audience to buy anything.**

Marketing should educate, entertain, solve practical problems, and build trust.

The studio combines AI-assisted research, creative production, and strategic planning while keeping people responsible for final editorial decisions and publishing.
