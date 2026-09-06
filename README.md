# Product Management Playbook

A practical, reusable library of Product Management skills for turning ambiguous problems into clear decisions, strong product strategies, and executable plans.

This repository is designed for **both product managers and AI agents**. Each skill captures a repeatable way of thinking about a common PM problem, so you can use the same framework whether you are working alone, collaborating with a team, preparing for an executive discussion, or asking an AI assistant to help you.

## What this repository is for

Product management often looks like a collection of unrelated activities: customer discovery, market analysis, strategy, prioritization, business cases, requirements, roadmaps, metrics, and executive communication.

In practice, these activities are connected.

A good PM starts with a customer or business problem, builds enough understanding to make a decision, evaluates options, chooses a direction, aligns stakeholders, and then turns the decision into something a team can execute and measure.

This repository gives you a set of **building blocks for that workflow**.

Rather than giving you one rigid methodology, the playbook provides focused skills that you can combine depending on the situation.

## How to think about the skills

Each skill is intentionally small and focused on one job.

For example:

- `customer-problem-definition` helps turn a vague request into a clearly defined problem worth solving.
- `customer-discovery` helps structure what you need to learn from customers and how to turn conversations into evidence.
- `market-sizing` helps estimate the size and shape of an opportunity.
- `competitive-analysis` helps understand alternatives, differentiation, and strategic positioning.
- `product-strategy` helps connect the problem, customer, market, choices, and desired outcomes into a coherent direction.
- `prioritization` helps make trade-offs explicit when resources are limited.
- `business-case` and `roi-analysis` help translate product opportunities into economic decisions.
- `product-requirements` helps turn a chosen direction into something teams can build.
- `product-roadmap` helps communicate sequencing, outcomes, and dependencies over time.
- `product-metrics` helps define how success will be measured after launch.
- `executive-decision-memo`, `six-pager`, and `stakeholder-alignment` help communicate decisions to senior stakeholders.
- `ai-product-strategy` and `agentic-workflow-design` extend the same PM thinking to AI-native and agentic products.

The goal is not to use every skill every time. The goal is to **pick the smallest set of skills that gets you from question to decision to action**.

## Typical product workflow

A common end-to-end workflow might look like this:

```text
Customer problem
      ↓
Customer discovery
      ↓
Market + competitive understanding
      ↓
Product strategy
      ↓
Strategic options
      ↓
Prioritization
      ↓
Business case / ROI
      ↓
Requirements
      ↓
Roadmap
      ↓
Metrics
      ↓
Stakeholder alignment
```

This is a guide, not a mandatory process. In real product work, you will often move back and forth between these steps.

For example, new customer evidence may change the problem definition. A market-sizing exercise may change the strategy. A business case may eliminate an otherwise attractive idea. A technical constraint may change the roadmap.

The skills are meant to support that iterative way of working.

## What's inside each skill

Each folder contains two files:

### `SKILL.md`

This is the **execution guide**.

It explains how an AI agent or PM should approach the problem, what inputs are useful, what analysis should be performed, and what a strong output should contain.

The instructions are written to be reusable and vendor-neutral, so they are not tied to a specific AI model or platform.

### `README.md`

This is the **human-friendly guide**.

It explains when to use the skill, what kind of problem it solves, the information you should provide, what the output should look like, and examples of how to apply it.

## Using the playbook with AI

The repository is designed to work with modern AI assistants such as Claude, ChatGPT, Gemini, Codex, Copilot, and other agentic tools.

You can use an individual skill as a prompt-like operating procedure. Give the AI the business context, relevant evidence, constraints, and the desired decision, then ask it to apply the skill.

For example:

> Use the `market-sizing` skill to estimate the addressable market for a new B2B payments capability. Start with the assumptions you need, distinguish facts from estimates, show the calculation, and identify the biggest uncertainties.

Or combine skills:

> Use `customer-problem-definition` and `customer-discovery` to help me determine whether this customer request represents a broad market problem or a one-off feature request.

For more complex work, you can chain several skills together:

```text
Problem definition
        →
Discovery
        →
Strategy
        →
Options
        →
Prioritization
        →
Business case
        →
Requirements
        →
Roadmap
        →
Metrics
```

The repository also includes `AGENTS.md`, which provides general guidance for AI agents working with the playbook.

## Using the playbook as a PM

You do not need an AI tool to use these skills.

Treat each `SKILL.md` as a lightweight checklist for structured thinking. The frameworks are especially useful when you are facing situations such as:

- "We have a customer request, but I am not sure it is a real problem."
- "We have several strategic options and need to choose one."
- "Leadership wants a business case before funding this initiative."
- "Engineering needs clearer product requirements."
- "The roadmap has too many commitments and not enough capacity."
- "We need to explain a complicated decision to executives."
- "We are building an AI feature, but we are not sure whether AI should actually be part of the product experience."

The value of the playbook is the structure it provides before you jump into the answer.

## Design principles

### Outcome over activity

Start with the customer, business, or strategic outcome you are trying to change. Avoid treating documents, features, launches, or roadmaps as the outcome itself.

### Evidence over opinion

Separate what you know from what you assume. Make uncertainty visible rather than hiding it behind precise-looking numbers or confident language.

### Trade-offs are part of the job

Good product decisions usually involve competing priorities. The skills are designed to make those trade-offs explicit rather than pretending every idea can be pursued.

### Simple enough to use

A framework only helps if a PM can actually use it. Each skill is intentionally practical and can be adapted to the size and maturity of the problem.

### Vendor neutral

The playbook is not tied to a particular company, AI model, software tool, or product methodology. The underlying product thinking should remain useful as tools change.

### AI-ready, human-led

AI can accelerate analysis, synthesis, writing, and exploration. Product judgment still matters. The strongest use of these skills is to combine structured AI assistance with human context, judgment, and accountability.

## Skill directory

| Skill | Primary purpose |
|---|---|
| `business-case` | Build an investment case for a product or initiative |
| `competitive-analysis` | Understand competitors, alternatives, and differentiation |
| `customer-discovery` | Plan discovery and turn conversations into evidence |
| `customer-problem-definition` | Define the customer problem clearly before solutioning |
| `market-sizing` | Estimate market opportunity and key assumptions |
| `product-strategy` | Define where to play, how to win, and what outcomes matter |
| `strategic-options` | Frame meaningful choices and compare strategic paths |
| `prioritization` | Make transparent trade-offs across competing opportunities |
| `prfaq` | Create a press release and FAQ to clarify product value |
| `product-requirements` | Translate strategy into clear requirements for delivery |
| `product-roadmap` | Sequence initiatives around outcomes, timing, and dependencies |
| `roi-analysis` | Evaluate expected economic value and return |
| `build-buy-partner` | Decide whether to build, buy, partner, or combine approaches |
| `platform-strategy` | Define platform value, capabilities, consumers, and evolution |
| `product-metrics` | Define success measures, leading indicators, and guardrails |
| `ai-product-strategy` | Apply PM strategy thinking to AI-enabled products |
| `agentic-workflow-design` | Design workflows where AI agents take meaningful actions |
| `executive-decision-memo` | Communicate a decision and recommendation to executives |
| `six-pager` | Structure a concise narrative for complex product decisions |
| `stakeholder-alignment` | Create shared understanding, resolve disagreement, and drive decisions |

## A simple way to get started

Start with the question you are actually trying to answer.

Then choose the skill that best matches that question rather than starting with a document type.

For example:

**"Should we build this?"**

Start with `customer-problem-definition`, then consider `customer-discovery`, `market-sizing`, `strategic-options`, and `business-case`.

**"What should we build next?"**

Start with `prioritization`, but bring in `product-strategy`, `product-metrics`, or `customer-discovery` when the decision needs more context.

**"How do I get leadership aligned?"**

Use `executive-decision-memo`, `six-pager`, or `stakeholder-alignment` depending on the situation.

**"How should we approach an AI or agentic product?"**

Start with `ai-product-strategy` or `agentic-workflow-design`, then use the broader PM skills for market, economics, prioritization, requirements, and measurement.

## Philosophy

The intent of this repository is simple: **make good product thinking easier to repeat.**

The individual skills are useful on their own, but they become more powerful when combined into a repeatable product-development and decision-making system.

Use them as frameworks, adapt them to your context, and keep improving them as you learn.
