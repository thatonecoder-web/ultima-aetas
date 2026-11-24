
# ULTIMA AETAS
## Development Principles

**Document Version:** 0.1  
**Status:** Early Development  
**Project:** ULTIMA AETAS

> **Development Disclaimer:** ULTIMA AETAS is under early development. All concepts, features, mechanics, systems, and content are subject to change.

---

# 1. Purpose

This document establishes the fundamental principles guiding the development of ULTIMA AETAS.

It defines how design decisions should be evaluated, how development priorities should be established, and what standards should be maintained throughout the project.

These principles apply to gameplay design, narrative development, technical architecture, worldbuilding, documentation, and future expansions.

The objective is to maintain a consistent creative and technical direction while allowing the project to evolve during development.

# 2. Core Development Principles

## 2.1 Preserve the Game's Identity

Every major development decision should support the central identity of ULTIMA AETAS.

The game is built around two central themes:

- Humanity's struggle for survival following the collapse of civilization.
- The transformation of human relationships, morality, identity, and society under extreme circumstances.

Survival provides the immediate gameplay experience. Human relationships and societal change provide the wider narrative experience.

Features that do not meaningfully support the game's identity should be evaluated carefully before implementation.

## 2.2 Prioritize Meaningful Gameplay

Gameplay systems should provide meaningful interactions, decisions, or consequences.

Complexity alone does not make a system valuable.

Every major mechanic should have a clear purpose within the overall experience.

For example:

- Weather should influence survival and exploration.
- Reputation should influence social interactions and opportunities.
- Faction politics should influence the wider world.
- Character relationships should influence dialogue, decisions, and narrative outcomes.
- Resource management should influence the player's ability to survive and support others.

Systems should interact where appropriate, creating an interconnected gameplay experience.

## 2.3 Build Gradually

ULTIMA AETAS is an ambitious project and must be developed incrementally.

Development should prioritize establishing functional foundations before introducing increasingly complex systems.

A feature should be implemented, tested, evaluated, and refined before becoming a dependency for additional systems.

The project should avoid attempting to develop the entire planned game simultaneously.

## 2.4 Quality Over Feature Quantity

The quality, reliability, and integration of existing systems should take priority over the number of implemented features.

A smaller collection of functional, interconnected mechanics is preferable to a large collection of unfinished or superficial features.

Features should not be considered complete simply because they exist in the codebase.

They must function as intended and integrate properly with relevant systems.

# 3. Gameplay Design Principles

## 3.1 Player Agency

Players should have meaningful control over their decisions and approaches to survival.

The game should support different approaches to problems, including:

- Negotiation.
- Cooperation.
- Avoidance.
- Investigation.
- Trade.
- Employment.
- Exploration.
- Conflict.

The game should avoid unnecessarily forcing players into a single approach when reasonable alternatives exist.

Player decisions should have consequences appropriate to their circumstances.

## 3.2 Consequential Decisions

Important decisions should be treated with narrative and systemic significance.

Consequences may affect:

- Characters.
- Relationships.
- Settlements.
- Organizations.
- Political structures.
- Available opportunities.
- Regional conditions.
- Campaign progression.
- Final outcomes.

Consequences may be immediate, delayed, indirect, or dependent on subsequent events.

The game should avoid reducing major decisions to simple dialogue selections with interchangeable outcomes.

## 3.3 Avoid Artificial Consequence Notifications

The game should generally avoid immediately explaining every consequence of a player's actions.

Characters should respond naturally, and the player should learn about developments through the world.

Possible sources of information include:

- Conversations.
- Rumours.
- News and broadcasts.
- Personal observations.
- Organizational communications.
- Changes in character behaviour.
- Changes in settlement conditions.

The player should be able to interpret events without constantly receiving explicit explanations from the interface.

## 3.4 Survival Should Remain Relevant

Survival mechanics should remain meaningful throughout the campaign.

Food, water, temperature, fatigue, injuries, clothing, and equipment should influence gameplay.

These systems should remain relevant even when the player becomes politically influential or assumes leadership responsibilities.

Progression should introduce new capabilities and responsibilities without eliminating the importance of survival.

## 3.5 Multiple Viable Playstyles

The game should support different approaches to living in the world.

Players may focus on professions, trade, exploration, relationships, faction involvement, political leadership, or other activities.

Combat should not be the only meaningful form of progression.

Avoiding confrontation and maintaining a peaceful livelihood should remain viable approaches where the circumstances allow.

# 4. World Simulation Principles

## 4.1 An Independent World

The world should operate independently of the player's immediate actions.

NPCs, factions, settlements, and other organizations should have their own interests and activities.

The player should not be treated as the centre of every event.

World developments should emerge from the interactions of characters, organizations, environmental conditions, and available resources.

## 4.2 Consistent World Rules

World systems should follow consistent internal rules.

Environmental conditions, character behaviour, faction interactions, resource availability, and political developments should be governed by understandable logic.

Exceptions may exist for narrative purposes, but they should be intentional and appropriately established.

## 4.3 Persistent Consequences

Important world developments should be reflected in the simulation.

Examples include:

- A settlement losing access to a major supply route.
- A faction experiencing a leadership change.
- A community recovering from a major disaster.
- A previously reliable trading partner becoming hostile.
- A character changing their opinion of the player.
- An organization expanding its influence into another region.

The world should retain relevant history rather than treating major events as temporary encounters.

## 4.4 Plausible Character Behaviour

NPCs should behave according to their circumstances, personalities, knowledge, relationships, responsibilities, and motivations.

Characters should not possess information they could not reasonably have acquired.

Information should travel through plausible channels.

A character's position within an organization should influence what they know, what they can disclose, and how they interact with the player.

## 4.5 World Simulation and Performance

World simulation should balance complexity with technical performance.

Not every character or environmental system needs to operate at maximum simulation detail at all times.

Simulation detail may be adjusted according to relevance, distance, activity, and available computing resources.

However, optimization should preserve important world continuity and avoid producing contradictory outcomes.

The initial single-player experience should pause world progression when the player suspends or closes the game.

# 5. Narrative Development Principles

## 5.1 Earned Emotional Investment

Emotional moments should be supported by character development and established relationships.

Characters should have personalities, personal histories, motivations, and lives beyond their involvement in the main storyline.

Players should have opportunities to spend time with characters during ordinary gameplay.

Important narrative events should build upon experiences the player has already shared with those characters.

## 5.2 Consequential Character Relationships

Relationships should develop over time and respond to player behaviour.

Characters may remember:

- Promises.
- Betrayals.
- Acts of kindness.
- Shared experiences.
- Conflicts.
- Important decisions.
- Treatment of other individuals.

Relationships should not be reduced to simple numerical affection scores.

## 5.3 Narrative Continuity

Major events should have lasting consequences within the campaign.

Dialogue, missions, character availability, faction relationships, and world conditions should reflect relevant previous events.

The narrative should account for the player's history wherever technically and creatively practical.

## 5.4 Meaningful Campaign Variations

Different decisions and narrative opportunities should produce meaningful variations in the campaign.

The project should prioritize coherent branching narratives with interconnected consequences.

The number of endings should not be used as the primary measurement of narrative depth.

Different endings should reflect the player's decisions, relationships, organizational involvement, and the condition of the world.

## 5.5 Respect Narrative Independence

Major narrative branches should have their own identities, conflicts, characters, and progression.

For example, founding an independent faction introduces a distinct narrative branch that fundamentally affects the main campaign and its eventual ending.

The three major faction-founding opportunities are reserved for detailed development in the world and lore documentation.

Narrative branches should remain connected to the wider world where appropriate.

# 6. Faction and Political Design Principles

## 6.1 Distinct Organizational Identities

Factions should possess distinct political structures, cultures, priorities, and methods of exercising authority.

Government institutions, criminal organizations, corporations, trade guilds, military formations, and independent settlements should not operate identically.

## 6.2 Internal Complexity

Organizations may contain competing interests, personal ambitions, rivalries, and disagreements.

The extent of internal conflict should depend on the organization's structure and culture.

Political complexity should emerge naturally from the distribution of authority and competing interests.

## 6.3 Dynamic Political Structures

Factions should be capable of changing their leadership and governing systems over time.

Political transformations may occur through leadership succession, institutional instability, internal conflict, military intervention, economic pressure, or other circumstances.

The player may influence these developments, but should not control every political event in the world.

## 6.4 Authority Requires Responsibility

Political influence and leadership should introduce responsibilities and consequences.

Players who assume leadership positions should face the challenges associated with managing people, resources, security, diplomacy, and internal disagreements.

Authority should create meaningful gameplay and narrative opportunities.

# 7. Technical Development Principles

## 7.1 Browser-First Development

The initial development target is a single-player browser game.

The game should be playable in Google Chrome and compatible modern browsers.

Performance on ordinary computers should remain a major consideration.

## 7.2 Modular Architecture

Systems should be organized into clearly defined modules with responsibilities that are easy to understand and maintain.

Examples include:

- Player systems.
- NPC systems.
- Infected AI.
- Inventory.
- Survival.
- Environmental simulation.
- World simulation.
- Faction systems.
- Narrative systems.
- Save and load functionality.
- Rendering and user interface.

Modules should interact through clearly defined interfaces rather than relying on unnecessary dependencies.

## 7.3 Separation of Logic and Presentation

Core gameplay logic should remain independent of rendering and platform-specific functionality wherever practical.

The architecture should separate:

- Gameplay simulation.
- Rendering.
- User interface.
- Input handling.
- Persistence and save management.
- Platform-specific functionality.

This approach should make the project easier to maintain and leave room for possible future adaptation.

## 7.4 Performance and Resource Management

The game should prioritize efficient use of computing resources.

Development should consider:

- Rendering performance.
- Memory usage.
- Simulation update frequency.
- NPC processing.
- Infected AI processing.
- Asset loading.
- Save file size.
- Browser compatibility.

Optimization should be introduced when supported by profiling and testing rather than relying exclusively on assumptions.

## 7.5 Future Adaptability

The initial architecture should avoid unnecessary restrictions that would make future desktop adaptation difficult.

However, potential future platforms should not complicate the initial browser alpha without a clear technical justification.

The first development target remains the browser experience.

A future first-person desktop adaptation is conditional and subject to evaluation after the alpha.

## 7.6 Maintainable Code

Code should be understandable, organized, and maintainable.

Development standards should include:

- Clear naming conventions.
- Consistent formatting.
- Appropriate comments.
- Reusable components where practical.
- Defined interfaces.
- Error handling.
- Documentation for complex systems.
- Avoidance of unnecessary duplication.

Code should be written with future maintenance and expansion in mind.

# 8. Testing and Quality Assurance

## 8.1 Functional Testing

Every implemented system should be tested to verify that it behaves as intended.

Testing should include normal gameplay, edge cases, unexpected interactions, and failure conditions.

## 8.2 System Integration

Individual systems should be tested both independently and in combination.

A feature that functions in isolation may still create problems when interacting with other systems.

Examples include:

- Weather interacting with clothing and temperature.
- NPC relationships interacting with reputation.
- Faction politics interacting with mission availability.
- Inventory interacting with crafting and equipment.
- World simulation interacting with save and load functionality.

## 8.3 Regression Testing

Changes to existing systems should be tested for unintended effects on previously functional features.

Important gameplay functionality should remain stable as the project expands.

## 8.4 Performance Testing

Performance should be evaluated on hardware representative of the intended audience.

Testing should consider situations involving larger numbers of characters, environmental systems, and simultaneous world activities.

## 8.5 Honest Development Status

Features should be clearly classified according to their actual development state.

Suggested classifications:

- **Planned:** Intended for future development.
- **In Development:** Currently being implemented.
- **Prototype:** An experimental implementation.
- **Implemented:** Functionality has been added.
- **Tested:** Functionality has undergone appropriate testing.
- **Complete:** Meets its defined requirements and acceptance criteria.

A feature should not be described as complete merely because a preliminary implementation exists.

# 9. Development Scope and Prioritization

## 9.1 Alpha Priorities

The initial alpha should establish the foundational gameplay experience.

Development should prioritize a functional and playable browser game.

Potential priorities include:

- Player movement.
- World exploration.
- Basic environmental interaction.
- Initial survival mechanics.
- Inventory functionality.
- Basic infected behaviour.
- NPC interaction.
- Save and load functionality.
- Browser performance and stability.

The exact alpha feature list will be maintained in the development roadmap.

## 9.2 Feature Evaluation

Before introducing a major feature, development should consider:

1. Does it support the game's identity?
2. Does it provide meaningful gameplay or narrative value?
3. Does it interact with existing systems?
4. Is it technically feasible?
5. Can it be developed without destabilizing existing functionality?
6. Is it appropriate for the current development stage?

Features that cannot be justified should be postponed or reconsidered.

## 9.3 Scope Management

New ideas should be documented and evaluated before implementation.

A feature should not automatically become part of the development roadmap simply because it has been proposed.

The project should maintain a distinction between immediate priorities, future objectives, experimental concepts, and discarded ideas.

## 9.4 Development Milestones

Development should progress through identifiable milestones.

Each milestone should have defined objectives and criteria for evaluating completion.

The project should avoid moving forward solely because a certain amount of development time has passed.

Progress should be measured through working functionality, stability, and demonstrated results.

# 10. Documentation and Project Organization

## 10.1 Documentation Standards

Major systems should have appropriate documentation.

Documentation should explain:

- The purpose of the system.
- Its intended behaviour.
- Its interactions with other systems.
- Relevant technical requirements.
- Known limitations.
- Current development status.

Documentation should be updated when important design decisions change.

## 10.2 Source of Truth

Project documentation should serve as the primary reference for established design decisions.

When implementation differs from documentation, the discrepancy should be investigated and resolved.

Unconfirmed ideas should not be presented as finalized requirements.

## 10.3 Change Management

Significant design changes should be recorded.

Changes should include a brief explanation of:

- What changed.
- Why it changed.
- Which systems are affected.
- Whether existing documentation requires revision.

This helps preserve project continuity as development progresses.

# 11. Asset and Content Principles

## 11.1 Originality

ULTIMA AETAS should establish its own visual, narrative, and audio identity.

External media and existing games may provide inspiration, but the project should avoid directly copying protected creative material.

## 11.2 Consistency

Assets should be consistent with the game's established visual and atmospheric direction.

Characters, environments, interfaces, objects, and audio should contribute to a coherent world.

## 11.3 Asset Management

Project assets should be organized and documented.

Asset sources, ownership, licensing, and usage permissions should be tracked.

Third-party assets should only be incorporated when their licensing permits the intended use.

## 11.4 Content Integrity

Narrative and environmental content should support the game's themes and internal world logic.

Dark subject matter should serve a narrative, atmospheric, or gameplay purpose rather than relying exclusively on shock value.

# 12. Accessibility and Player Experience

Accessibility should be considered throughout development rather than treated exclusively as a final-stage addition.

Potential areas include:

- Readable interface elements.
- Adjustable audio levels.
- Clear gameplay feedback.
- Customizable controls where practical.
- Appropriate text readability.
- Options for reducing visual or audio intensity.
- Consistent interface behaviour.

The game should aim to provide a clear and understandable experience without unnecessarily simplifying its underlying systems.

# 13. Future Development

ULTIMA AETAS is intended to grow beyond its initial alpha.

Potential future development areas include:

- Expanded regional maps.
- Additional countries.
- More complex faction systems.
- Expanded political simulation.
- Additional professions and economic systems.
- More advanced NPC behaviour.
- Expanded narrative branches.
- Additional character perspectives.
- Possible first-person desktop adaptation.
- Potential future multiplayer exploration.

These are development possibilities rather than guaranteed deliverables.

Future expansion should depend on the stability, quality, and feasibility of the existing project.

---

# 14. Guiding Principle

ULTIMA AETAS should be developed as a coherent, interconnected world in which survival, human relationships, society, and history influence one another.

Every system should contribute to the experience of living in a world that continues to change, regardless of whether the player is present.

The project should prioritize meaningful experiences, consistent world rules, technical reliability, and long-term maintainability.

**The ultimate objective is to create a world that feels as though it has a history, a present, and a future of its own.**

---

# Document Maintenance

This document establishes the current development principles of ULTIMA AETAS.

It should be reviewed as the project evolves and revised when major development priorities or technical requirements change.

All principles remain subject to refinement during early development.

