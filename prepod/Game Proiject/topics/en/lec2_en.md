# Creating Any Software

## Introduction

Software development is not just about writing code, but about an entire system of approaches and methodologies. The choice of approach affects team efficiency, product quality, and adaptability to change.  

For a game designer, understanding these models is important because games are developed like any other software — but with the added complexity of emotional and artistic content. Some studios use classical methodologies (like **Waterfall** in AAA projects), while others use agile ones (like **Agile** in mobile and live-service games).  

## Types of Software Development

1. **Waterfall**
   - Clear plan, stages, deadlines  
   - Best for projects with well-defined requirements  
   - **Cons**: hard to introduce changes, high risk of late-stage errors  

2. **Agile Development**
   - Iterative process, frequent releases  
   - Works well when requirements may change  
   - **Cons**: requires discipline, may become chaotic without good management  

3. **Scrum**
   - A subset of Agile with defined roles and rituals  
   - Useful for teams wanting to structure Agile  

4. **Kanban**
   - Task visualization on a board, continuous workflow  
   - Good for teams with ongoing streams of tasks  

5. **DevOps**
   - Integration of development and operations  
   - Fits projects with frequent releases and need for high availability  
   - **Cons**: requires automation and strong collaboration culture  

6. **Spiral Model**
   - Risk-oriented iterations (cycles)  
   - Each cycle includes goals, risk analysis/mitigation, development/validation, and planning the next cycle  
   - **Cons**: complex to manage, costly, requires experienced teams  

7. **RAD (Rapid Application Development)**
   - Fast development using prototypes  
   - Works for projects with tight deadlines  
   - **Cons**: risks insufficient architectural design  

## Choosing an Approach

- Assess project requirements  
- Team size and experience  
- Flexibility and adaptability  
- Tools and technologies  

In this lecture, we’ll focus on **Waterfall**, **Spiral Model**, and **Agile**.

## Waterfall

> [!NOTE]  
> Waterfall is a traditional model where the process is divided into sequential phases. Each must be completed before the next begins. Backtracking is minimal.

![Waterfall model diagram](../../_images/02/02_waterfall.png)

**Phases of Waterfall:**

1. System requirements — define functional and non-functional requirements, documentation.
2. Software requirements — analyze requirements, create specifications.  
3. Analysis — system architecture, interface design.  
4. Design — prototypes, detailed architecture.  
5. Coding — programming, unit testing.  
6. Testing — integration, system, acceptance.  
7. Deployment — rollout, user training.  

**Example from the game industry:**  
Early Blizzard practices (e.g., “Diablo II”) — heavy documentation, long cycles, high costs for late changes.

## Spiral Model (Boehm)

> [!NOTE]  
> The Spiral Model is a risk-driven iterative process. Each loop of the spiral is a mini-project: goals are refined, risks identified and reduced (often through prototyping), an increment of the product is created and verified, and then the next iteration is planned.

![Spiral model diagram](../../_images/02/02_spiral.png)

Four quadrants of each loop:

1. Goals, alternatives, constraints — define tasks and success criteria.  
2. Risk analysis and mitigation — research, prototypes, experiments, technical trials.  
3. Development and validation — build increment (model/module/version), test and verify.  
4. Planning the next iteration — assess results, document decisions, plan work and budget.  

**When to use:**  

- Large/long-term projects with high uncertainty.  
- High technical risks (custom engine, performance, networking, new platform).  
- Strict quality and safety requirements, need for early prototypes.  

**Artifacts:**  

- Risk log, experiment/prototype reports, exit criteria.  
- Product increment, verification report, next cycle plan.  

**Pros / Cons:**  
*Pros:* risk handled early, early prototyping, gradual refinement of requirements.  
*Cons:* complex and costly, needs mature processes and expertise.  

**Connection to Game Design:**  
Works well for projects with innovative mechanics and technical novelty: start with cheap “trials” (paper/digital prototypes), then move to implementation and scaling.

## Agile (Flexible Development)

> [!Note]  
> Agile is an approach to software development focused on flexibility, collaboration, and fast delivery of working products. It is iterative, with short cycles (iterations), each producing a functional product.

**Microhistory of Agile (2001):**  
In 2001, 17 software developers gathered in Snowmass, Colorado, to discuss alternatives to traditional software development. They created the “Agile Manifesto,” defining four core values and twelve principles.

![Agile development diagram](../../_images/02/02_agile.png)

**12 Principles of Agile:**

1. Goal: satisfy the customer through fast and continuous delivery.  
2. Welcome changing requirements, even late in development.  
3. Deliver working software frequently (weeks to months).  
4. Close collaboration with the customer throughout the project.  
5. Build projects around motivated individuals, support them.  
6. Face-to-face communication is the best way to share information.  
7. Working software is the main measure of progress.  
8. Sustainable pace: sponsors, developers, users should maintain a steady rhythm.  
9. Continuous attention to technical excellence and good design improves agility.  
10. Simplicity — maximize the amount of work not done.  
11. Best architectures, requirements, and designs emerge from self-organizing teams.  
12. Teams regularly reflect on effectiveness and adjust accordingly.  

**Agile Implementation:**

1. Flexible goals (changes possible at all stages).  
2. Prioritized backlog (functional and non-functional requirements).  
3. Sprints (long-term goals broken into short cycles, max 1 month).  
4. Daily standups (short sync meetings with tasks and reports).  
5. Demo Day (end of each sprint, showing results to stakeholders).  
6. Retrospective (review what went well, what to improve, actions for next project).  

**Example from the game industry:**  
Live-service projects (e.g., “Fortnite”): frequent updates, seasonal events, quick reaction to metrics and feedback.

**Tips for Effective Prototyping:**

1. Each prototype must have a clear purpose.  
2. Forget about quality.  
3. Don’t get attached.  
4. Prioritize prototypes.  
5. Combine them effectively.  
6. Prototypes don’t have to be digital.  
7. They don’t have to be interactive.  
8. Use editable game engines.  
9. Sometimes it’s better to make a toy.  
10. Grab any opportunity.  

*Repeat the cycle.*

> [!Important]  
> **Rule of Two Fifties:**  
> Plan your budget so that you can finish the project successfully with only 50% of the planned resources.  
> By mid-project, all core gameplay elements should already be implemented.  

## Comparison: Waterfall, Spiral, and Agile

| Criterion         | Waterfall                              | Spiral Model                               | Agile                                   |
|-------------------|----------------------------------------|--------------------------------------------|-----------------------------------------|
| Approach          | Sequential                             | Risk-driven iterations (goals → risks → build → plan) | Iterative, incremental                  |
| Flexibility       | Low                                    | Medium–high (thanks to risk review and prototypes) | High                                    |
| Requirements      | Fixed                                  | Refined each cycle based on risk analysis and prototypes | Change continuously via backlog priority |
| Quality control   | At the end                             | Each cycle via prototypes and verification  | At every stage                          |
| Game examples     | “Diablo II” (Blizzard, 2000)           | Innovative AAA projects with custom engines | “Fortnite” (Epic Games, 2017–…)         |
| Best for          | Large projects with fixed specs        | Large/long-term projects with uncertainty and risks | Live-service and indie projects         |

## Conclusion

Choosing a development approach depends on many factors: team size and experience, project requirements, level of uncertainty and risk. Understanding different models helps game designers work effectively with dev teams, adapt to change, and create quality games.
