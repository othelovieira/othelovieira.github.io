## Microsoft Copilot Studio Terms - Crash Course Edition

Microsoft Copilot Studio uses a set of core terms to describe how AI agents are built, connected to data, and run.

**Core** **Building** **Blocks**

-  Agent: An AI assistant or worker built to answer questions, reason over data, and complete tasks or automations.

-  Instructions: The rules, role, tone, and guidance that shape how an agent behaves and responds.

-  Knowledge Sources: Files, SharePoint sites, websites, or databases attached to an agent so its answers stay grounded in trusted data.

-  Tools / Actions: Capabilities that let an agent interact with external systems, run prompts, call APIs, or update records.

-  Skills: Reusable sets of instructions for specific tasks that load when a user's request matches their description.

-  Topics: Defined conversation paths, triggers, and branching logic used to handle specific intents or structured flows.

-  Workflows: Automated, multi-step sequences that run on triggers or orchestrate tasks without manual steps.

**Data**, **Connections** **&** **Runtime**

-  Connectors: Pre-built or custom bridges that link Copilot Studio to apps and services like Teams, Dataverse, SharePoint, or external APIs.

-  Grounding: Linking an agent's responses to specific organizational data rather than relying only on general model knowledge.

-  Harness: The underlying runtime architecture an agent uses to process requests such as the Microsoft Copilot harness (reasoning dynamically from instructions, knowledge, and tools) or the Customer Conversation harness (multi-agent voice/chat flows with human escalation).

-  Triggers: Events or conditions that start an agent, topic, or workflow automatically.

-  Variables & Entities: Stored values and recognizable data types (such as names, IDs, or dates) extracted and passed across steps during a conversation.

**Administration** & **Governance**

-  Environments: Isolated Power Platform spaces where agents, data, and resources are managed and separated (such as development vs. production).
-  Data Loss Prevention (DLP): Admin policies that block sensitive information from being shared across connectors or exposed in outputs.
-  Governance: Admin controls covering access permissions, approved knowledge sources, compliance, and usage billing (such as capacity or credits).

<div align="center">
This post was written with ❤️ and ☕️
</div>
