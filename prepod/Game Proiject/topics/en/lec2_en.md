# Lecture: Fundamentals of Video Game Design

## Introduction

Video game design is a multifaceted process that combines creative vision, technical skills, and systems thinking. Modern game design requires an understanding not only of game mechanics, but also of software principles, project management, and documentation.

## Game Design Document (GDD — Game Design Document)

### What is a Game Design Document?

A **Game Design Document (GDD)** is a central document that describes every aspect of a game, from its concept and mechanics to its technical implementation and artistic style. It is the project’s “bible” and serves as a single source of truth for the entire development team, including designers, programmers, artists, sound designers, and producers.

A GDD evolves throughout the development cycle. It begins as a brief description of the concept and gradually becomes more detailed as design decisions are made. A good GDD should be detailed enough for any team member to understand what needs to be implemented while remaining flexible enough to accommodate changes.

### Main GDD Sections

A game design document is built around **four main directions, or pillars of game design**:

1. **Technology**
2. **Mechanics**
3. **Story/Narrative**
4. **Aesthetics**

Let us examine each pillar and its subcategories in detail.

## 1. Technology

The technology section describes the technical foundation of the game: the engine, platforms, development tools, and technical limitations.

### Subcategories

#### 1.1. Game Engine and Technologies

- **Engine selection**: Unity, Unreal Engine, Godot, or a proprietary engine
- **Engine version** and the rationale for choosing it
- **Plugins and middleware**: physics systems such as PhysX and Havok, audio tools such as FMOD and Wwise, and animation systems
- **Programming languages**: C#, C++, Python, and Lua for scripting

#### 1.2. Platforms and Compatibility

- **Target platforms**: PC (Windows, macOS, Linux), consoles (PlayStation, Xbox, Nintendo Switch), mobile devices (iOS, Android), and VR/AR
- **Minimum and recommended system requirements**
- **Cross-platform support**: support for multiplayer between platforms
- **Platform-specific features**: controls, performance, and limitations

#### 1.3. Network Architecture for Online Games

- **Network type**: P2P, client-server, or an authoritative server
- **Protocols**: TCP/UDP and WebSocket
- **Server infrastructure**: cloud solutions such as AWS, Azure, and Google Cloud
- **Scalability**: handling peak loads and matchmaking

#### 1.4. Development Tools

- **Version control systems**: Git, Perforce, and SVN
- **Designer tools**: level editors, dialogue editors, and visual scripting systems
- **CI/CD pipelines**: automated builds, testing, and deployment
- **Profiling and debugging**: tools for performance analysis

#### 1.5. Technical Constraints and Risks

- **Performance budget**: FPS, memory consumption, and loading time
- **Storage constraints**: build size, patches, and DLC
- **Technical risks**: dependence on third-party SDKs and licensing

## 2. Mechanics

Mechanics are the rules and systems that define how the player interacts with the game world. They represent how the game works at a fundamental level.

### Subcategories

#### 2.1. Core Game Mechanics

- **Player actions**: movement, attacking, interaction, building, and exploration
- **Game loop**: what the player does every second, minute, and hour
- **Progression**: how the player becomes stronger or more capable through levels, skills, and equipment
- **Feedback**: how the game responds to player actions visually, through sound, and through haptic effects

#### 2.2. Combat System, if applicable

- **Combat type**: melee, ranged, magical, or stealth-based combat
- **Balance**: damage, health, defense, and cooldowns
- **Enemy AI**: behavior, attack patterns, and adaptability
- **Combos and special moves**: action chains and rewards for mastery

#### 2.3. Economy and Resources

- **Currencies**: gold, crystals, experience points, and energy
- **Sources of resources**: rewards, trading, crafting, and farming
- **Resource spending**: upgrades, item purchases, and progression acceleration
- **Inflation and balance**: preventing exploits and preserving resource value

#### 2.4. Progression System

- **Levels and experience**: experience formulas and level requirements
- **Skills and perks**: skill trees and specialization choices
- **Achievements and trophies**: long-term motivational goals
- **Ranks and leaderboards**: competitive elements

#### 2.5. Physics and World Interaction

- **Physics engine**: gravity, collisions, and destructibility
- **Interactive objects**: doors, chests, switches, and vehicles
- **Environmental mechanics**: weather, time of day, and elemental effects

#### 2.6. Social Mechanics

- **Multiplayer**: cooperative play, PvP, and large-scale battles
- **Guilds and clans**: group progression and shared goals
- **Player-to-player trading**: auctions and direct exchange
- **Social features**: chat, friends, and invitations

## 3. Story/Narrative

The story creates an emotional connection between the player, the world, and its characters, giving meaning to the player’s actions.

### Subcategories

#### 3.1. Plot and Narrative Structure

- **Main quest**: the central story and the hero’s arc
- **Side quests**: additional stories that expand the world
- **Structure**: linear, nonlinear, branching, or open-ended
- **Narrative pacing**: the balance between action and story moments

#### 3.2. World and Lore

- **Setting**: fantasy, science fiction, historical, or post-apocalyptic
- **Geography**: maps, regions, and key locations
- **World history**: past events, mythology, and legends
- **Cultures and factions**: peoples, organizations, motivations, and conflicts

#### 3.3. Characters

- **Protagonist**: backstory, motivation, personality, and development
- **Antagonist**: goals, philosophy, and relationship with the hero
- **Supporting characters**: allies, mentors, and comic-relief characters
- **NPCs**: dialogue, schedules, and relationships with the player

#### 3.4. Dialogue and Narrative Techniques

- **Dialogue format**: text-based, voiced, or branching
- **Player choice**: consequences, moral dilemmas, and multiple endings
- **Exposition**: how information is presented through cutscenes, records, dialogue, and the environment
- **Show, Don’t Tell**: using the environment to convey the story

#### 3.5. Tone, Genre, and Themes

- **Tone and genre**: serious, comedic, dark, or satirical
- **Themes**: friendship, betrayal, redemption, freedom, and fate
- **Target audience**: age rating and cultural considerations

## 4. Aesthetics

Aesthetics define the visual and auditory style of the game, creating its atmosphere and emotional impact.

### Subcategories

#### 4.1. Visual Style and Art Direction

- **Art style**: realism, stylization, pixel art, cel-shading, and low-poly
- **Color palette**: dominant colors and the use of color to create mood
- **Lighting**: daylight, nighttime, atmospheric, and dynamic lighting
- **Post-processing**: filters and effects such as bloom, motion blur, and depth of field

#### 4.2. Character Design

- **Character style**: proportions, level of detail, uniforms, and clothing
- **Animation**: movement, combat animations, emotions, and lip-sync
- **Customization**: the ability to change appearance and equipment
- **Icons and portraits**: UI elements representing characters

#### 4.3. Environment Design

- **Architecture**: building styles, interiors, and exteriors
- **Nature**: landscapes, vegetation, water, and sky
- **Detailing**: decoration, props, and atmospheric elements
- **Navigation**: how the player finds their way through the space

#### 4.4. User Interface and User Experience (UI/UX)

- **HUD**: health, mana, minimap, and objectives
- **Menus**: main menu, inventory, map, and settings
- **Icons and symbols**: clarity, style, and consistency
- **UI animations**: transitions, notifications, and feedback

#### 4.5. Audio Design

- **Music**: the main soundtrack, combat music, exploration music, and emotional moments
- **Sound effects**: footsteps, gunshots, magic, environmental sounds, and UI sounds
- **Voice acting**: main characters, supporting characters, and narration
- **Audio mixing**: balancing music, effects, and dialogue
- **Spatial audio**: 3D sound, direction, and distance

#### 4.6. Atmosphere and Mood

- **Overall mood**: epic, dark, cheerful, or tense
- **Atmospheric effects**: fog, particles, weather, and time of day
- **Emotional peaks**: climactic moments and cutscenes

## Additional GDD Sections

In addition to the four main pillars, a complete game design document includes the following sections.

### 5.1. Concept and Vision

- **High Concept**: one or two sentences describing the essence of the game
- **Unique Selling Points (USPs)**: what makes the game unique
- **Target audience**: demographics, preferences, and platforms
- **References**: similar games and sources of inspiration

### 5.2. Gameplay Modes

- **Single-player campaign**: structure, duration, and difficulty
- **Multiplayer**: modes, maps, and balance
- **Additional modes**: arcade, survival, and speedrun modes

### 5.3. Monetization for Commercial Projects

- **Business model**: premium purchase, free-to-play, subscription, or hybrid
- **Microtransactions**: cosmetics, boosters, and loot boxes
- **DLC and expansions**: content planned after release
- **Monetization ethics**: avoiding predatory practices

### 5.4. Marketing and Launch

- **Release platforms**: where and when the game will launch
- **Promotional materials**: trailers, screenshots, and press kits
- **Community**: social media, Discord, and early access
- **Post-release support**: patches, content, and events

### 5.5. Appendices

- **Concept art**: characters, environments, and key scenes
- **Diagrams**: mechanics, world maps, and skill trees
- **Tables**: balance data, statistics, and formulas
- **Glossary**: terms, abbreviations, and names

## Software Development for Games

Game software development is a complex process that requires coordination between designers, programmers, artists, and other specialists. The chosen development methodology directly affects team efficiency, product quality, and the project’s ability to adapt to change.

### Types of Software Development Methodologies

There are many approaches to software development. The following is a brief list of the main methodologies:

- **Waterfall**
- **Agile development**
- **Scrum**
- **Kanban**
- **Lean**
- **DevOps**
- **Spiral development**
- **Rapid Application Development (RAD)**
- **Feature-Driven Development (FDD)**
- **Dynamic Systems Development Method (DSDM)**

The four most common methodologies used in the game industry are described in detail below.

### 1. Waterfall

**Waterfall** is a classic linear development methodology in which a project is divided into sequential stages. Each stage must be fully completed before the project moves to the next one.

![Waterfall model diagram](../../_images/02/02_waterfall.png)

#### Characteristics

- **Clear plan, stages, and deadlines**: the project is divided into fixed phases such as requirements analysis, design, implementation, testing, deployment, and maintenance, each with its own objectives and deadlines
- **Documentation-oriented process**: each stage is supported by detailed documentation that serves as the foundation for the next stage
- **Minimal change**: requirements are fixed at the beginning and are not expected to change during development

#### Suitable for

- Projects with **clear and stable requirements**
- Teams working on **predictable tasks**, such as porting or maintaining legacy code
- Situations where **contractual obligations** require a fixed scope of work

#### Advantages

- Simple planning and management
- Clear understanding of progress
- Strong documentation

#### Disadvantages

- **Changes are difficult to introduce**: any change in requirements may require the entire plan to be reviewed
- **Risk of late-stage errors**: bugs discovered during testing may require the design or code to be reworked
- **Lack of flexibility**: the player does not see the product until late in development, increasing the risk that it will not meet expectations
- **Long feedback cycle**: feedback from testers or clients arrives too late

#### Example in Game Development

Waterfall may be used for small projects with a fixed design, such as certain casual mobile games, or for porting a game to a new platform when the requirements are already known.

### 2. Agile Development

**Agile** is not a specific methodology but a philosophy and a set of principles described in the Agile Manifesto. Agile emphasizes flexibility, iteration, and continuous feedback.

![Agile process diagram](../../_images/02/02_agile.png)

#### Characteristics

- **Iterative process**: work is divided into short cycles, or iterations and sprints, at the end of which a working version of the product is created
- **Frequent releases**: each iteration ends with an increment that is potentially ready for release
- **Adaptability**: requirements can change even in the later stages of development
- **Customer focus**: continuous feedback from the client or stakeholders

#### Suitable for

- Projects with **changing requirements**
- Teams working in a **rapidly changing environment**, such as startups and indie development
- Situations where it is **important to obtain an MVP quickly** and test hypotheses

#### Advantages

- Flexibility and adaptability to change
- Early detection of problems
- Continuous feedback
- High team involvement

#### Disadvantages

- **Requires strong discipline**: without self-organization, the team may lose focus
- **Can become chaotic without good management**: the absence of a clear plan may lead to scope creep
- **Difficult schedule estimation**: it can be difficult to predict when the project will be completed
- **Requires continuous stakeholder involvement**: if stakeholders are unavailable, the process slows down

#### Agile Principles in Brief

1. Individuals and interactions are more important than processes and tools.
2. Working software is more important than comprehensive documentation.
3. Customer collaboration is more important than contract negotiation.
4. Responding to change is more important than following a plan.

#### Example in Game Development

Most modern game studios use Agile practices, especially during the early stages of development, when the design is still being shaped through prototyping and testing.

### 3. Scrum

**Scrum** is a specific framework that implements Agile principles. Scrum adds structure through clearly defined roles, events, and artifacts.

![Scrum process diagram](../../_images/02/02_scrum.png)

#### Characteristics

- **An Agile framework with clear roles and ceremonies**: Scrum defines who does what and when
- **Sprints**: fixed iterations, usually lasting two to four weeks, during which the team works on a defined set of tasks
- **Roles**:
  - **Product Owner**: represents the customer’s interests and manages the Product Backlog
  - **Scrum Master**: facilitates the process, removes obstacles, and helps the team follow Scrum practices
  - **Development Team**: a cross-functional group of programmers, designers, artists, and other specialists who create the product
- **Ceremonies**:
  - **Sprint Planning**: planning the work for the sprint
  - **Daily Scrum**: short daily meetings for synchronization
  - **Sprint Review**: demonstrating the sprint results to stakeholders
  - **Sprint Retrospective**: analyzing the process and identifying improvements

#### Suitable for

- Teams that want to **structure their Agile process**
- Projects where **transparency and predictability** are important
- Situations that require a **balance between flexibility and discipline**

#### Advantages

- Clear structure and accountability
- Regular feedback
- The ability to adapt between sprints
- High visibility into progress

#### Disadvantages

- **Ceremony overhead**: too many meetings can slow down the work
- **Requires a mature team**: inexperienced teams may follow Scrum mechanically without gaining its benefits
- **The Product Owner must be available**: if the PO is not involved, the backlog becomes unclear
- **Scaling difficulty**: Scrum can be difficult to apply to large projects with many teams and may require scaling frameworks such as SAFe or LeSS

#### Example in Game Development

Scrum is widely used in medium-sized and large studios where several teams, such as gameplay, graphics, audio, and QA, need to coordinate their work.

### 4. Kanban

**Kanban** is a method for visually managing work that originated in the Toyota Production System. In software development, Kanban focuses on a continuous flow of tasks and limiting work in progress, or WIP.

![Kanban board diagram](../../_images/02/02_kanban_example.jpg)

#### Characteristics

- **Task visualization on a board**: tasks are represented by cards that move through columns such as To Do, In Progress, Testing, and Done
- **Continuous workflow**: there are no fixed iterations; tasks are taken as resources become available
- **WIP limits**: each column has a limit on the number of tasks in progress, which prevents the team from becoming overloaded
- **Pull system**: the team pulls the next task when it is ready instead of receiving tasks according to a fixed schedule

![Example of a Kanban board](../../_images/02/02_kanban.jpg)

#### Suitable for

- Teams with a **continuous flow of tasks**, such as support, bug fixing, and content updates
- Situations where **priorities change frequently**
- Projects where a **quick response to requests** is important

#### Advantages

- Flexibility: priorities can be changed at any time
- Visual transparency: everyone can see the status of tasks
- No sprint-related overhead
- Focus on completing tasks rather than starting new ones

#### Disadvantages

- **Lack of fixed time frames**: without deadlines, tasks may take too long
- **Requires discipline**: the team must enforce WIP limits on its own
- **Planning difficulty**: it can be difficult to predict when a particular task will be completed
- **Less structure than Scrum**: it may not be sufficient for large projects

#### Example in Game Development

Kanban is often used for post-release game support, including bug fixing, balancing, and content updates, as well as by small indie teams.

## Other Development Methodologies in Brief

### 5. Lean

- **Focus**: eliminating waste and maximizing customer value
- **Principles**: reducing unnecessary documentation, optimizing processes, and continuous improvement
- **Application**: startups and projects with limited resources

![Lean process diagram](../../_images/02/02_lean.png)

### 6. DevOps

- **Focus**: integrating development and operations
- **Tools**: CI/CD, automation, monitoring, and infrastructure as code
- **Application**: projects with frequent releases, cloud services, and live-service products

![DevOps process diagram](../../_images/02/02_devops.jpeg)

### 7. Spiral Development

- **Focus**: iterative development with an emphasis on risk management
- **Structure**: each cycle includes planning, risk analysis, development, and evaluation
- **Application**: large projects with significant risks, including military, medical, and aerospace systems

![Spiral process diagram](../../_images/02/02_spiral.png)

### 8. Rapid Application Development (RAD)

- **Focus**: rapid development through prototyping and incremental delivery
- **Tools**: low-code/no-code platforms and visual builders
- **Application**: projects with strict deadlines, MVPs, and internal tools

![RAD process diagram](../../_images/02/02_rad.png)

### 9. Feature-Driven Development (FDD)

- **Focus**: development organized around features
- **Process**: modeling, creating a feature list, feature-based planning, feature-based design, and feature-based construction
- **Application**: large projects with clearly defined functionality

![FDD process diagram](../../_images/02/02_fdd.jpeg)

### 10. Dynamic Systems Development Method (DSDM)

- **Focus**: rapid delivery within fixed time and budget constraints
- **Principles**: active user involvement, frequent releases, and integrated testing
- **Application**: projects with strict time constraints

![DSDM process diagram](../../_images/02/02_dsdm.jpg)

## Choosing a Methodology for a Game Project

The choice of methodology depends on many factors, including team size, project requirements, flexibility, documentation needs, tools, technology, budget, and release strategy.

| Factor | Waterfall | Agile/Scrum | Kanban |
|---|---|---|---|
| **Team size** | Small teams | Medium and large teams | Any size |
| **Requirement clarity** | High | Medium or low | Low or changing |
| **Flexibility** | Low | High | Very high |
| **Documentation** | Detailed | Minimal or adaptive | Minimal or adaptive |
| **Release cycle** | One major release | Frequent increments | Continuous flow |
| **Risk management** | Mostly reactive | Proactive | Proactive |

### Recommendations

- **Indie development**: Agile or Kanban for flexibility
- **AA/AAA studios**: Scrum for structure and team coordination
- **Mobile F2P games**: Kanban for continuous updates
- **Ports and remasters**: Waterfall for predictability
- **Startups**: Lean and Agile for rapid MVP development

## Tips and Notes

> [!TIP]
> Start the GDD with a High Concept: one or two sentences that communicate and sell the game idea.

> [!TIP]
> Use visualizations: diagrams, concept art, and schematics are often easier to understand than text alone.

> [!TIP]
> Keep the GDD alive: update the document as the project evolves.

> [!TIP]
> Avoid excessive detail during the early stages: focus on the core mechanics.

> [!TIP]
> Involve the team: the GDD should be understandable to everyone, not only to the designer.

> [!NOTE]
> A GDD should not be a static document; it is a communication tool.

> [!NOTE]
> In Agile projects, some GDD information may be represented by a task backlog in Jira or Trello, but important design decisions should remain documented and accessible.

> [!NOTE]
> A short GDD of five to ten pages may be sufficient for a small project.

> [!NOTE]
> For AAA projects, a GDD may grow to hundreds of pages with appendices.

> [!WARNING]
> Do not write a GDD that is never used. The document must support the team’s actual work.

> [!WARNING]
> Avoid contradictions between sections, such as conflicts between mechanics and story.

> [!WARNING]
> Do not overload the concept stage with technical details that are not yet necessary.

> [!IMPORTANT]
> Use GDD templates to structure the document.

> [!IMPORTANT]
> Version the document, for example v1.0, v1.1, and v2.0.

> [!IMPORTANT]
> Store the GDD in an accessible location such as Confluence, Notion, or Google Docs.

> [!IMPORTANT]
> Link the GDD to tasks in a project tracker such as Jira or Asana.

## Conclusion

A game design document and the correct choice of development methodology form the foundation of a successful game project. The GDD provides a shared vision and coordinates the team, while the development methodology determines how effectively that vision will be implemented.

The modern game industry tends to favor flexible approaches such as Agile, Scrum, and Kanban because they make it possible to adapt to change and respond quickly to player feedback. However, traditional methods such as Waterfall remain relevant in certain situations.

The key to success is understanding the strengths and weaknesses of each methodology and choosing an approach that matches the specific project, team, and context.

## Additional Resources

### Books

- *The Art of Game Design: A Book of Lenses* — Jesse Schell
- *Level Up! The Guide to Great Video Game Design* — Scott Rogers
- *Agile Game Development* — Clinton Keith

### Online Resources

- Unity Learn and Unreal Online Learning
- Game Design Dojo and Game Maker’s Toolkit on YouTube

### GDD Templates

- Unity GDD Template
- Unreal Engine Documentation Templates
- Open-source GDD templates on GitHub
