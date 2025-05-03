# Abstract
AI-driven development is accelerating, yet most developers still interact with AI agents in a manual, sequential way, leading to inefficiencies and context switching. This paper proposes a workflow-first approach that integrates AI-driven automation with CI/CD pipelines, allowing developers to move from reactive iteration loops to continuous, system-driven optimization. By shifting the developer’s role from AI babysitter to orchestrator of intelligent feedback loops, we unlock deeper focus, improved developer experience, and a framework for sustainable, high-leverage software engineering.


# Idea

## Currently AI is blowing up and getting better every day
    - but we still have a manual dev culture around using it locally
    - applying it locally even with so-called agents we wait for them to finish
    - context switching leads to highly paid engineers essentially babysitting ai, thus relegating us
    - no joy in that

## an automation dev ops approach
    - focuses on dev experience, ergonom
    ics, dev experience and productivity
    - leverages time dev would spend waiting for ai agent to finish locally
    - current cycle of iteration i have seen as a developer using the best ai tools like cursor and others:
        - make change
        - run tests
        - tests fail
        - repeat
    - first ai prompt with modern composer agent in empty repo -> massive huge first step forward - YAY
    - yet soon we find ourselves caught in little bugs in multiple iterations using massive intelligence in 8, 9, 10 loops making teeny tiny baby steps
    - how do we optimize for steadiness, momentum, workflow, focus
    - the method / workflow:
        - instead of sequentially going thru those steps
        - an emphasis on the connections between the steps as a whole rather than treating them as indivudual stages or silos
        - naturally applies systems thinking
        - devs will take an "Outside and slightly elevated" posture
        - i am a developer, and this method is PRO developer JOY and MAX developer LEVERAGE
        - absolutely not about replacing the developer, in fact developers who embrace this will enjoy their careers more and get into flow state easier
        - even if the developer could automate their own role, they should, and would just move one step higher under this system
        - instead of applying, approving, saving, and pushing (monotonous, repetitive, untapped dev potential)
        - a new framework is proposed to elevate the developer to a different stance in the SDLC (should we call this SDLC orfocus on the cycle of iteration metnioned earlier?)
        - composing feedback loops to optimize signal from the iteration process
        - absolutely not about imposing structure
        - pull vs push (this is leaning towards pull most likely - trust, and the recursive leap of faith that structure emerges naturally, not thru hierarchy)
        - product design and thought culture that has a different way of thinking (most people can't think this way, thus a new method must be born and evangelized like dev ops once was)
        - yet another opportunity for developers will be to consult and spread the gospel of this "good news" framework, and be paid well doing it and have plenty of opportunities
        - books, trade shows, etc
        - more systems based, less sequential iteration rinse and repeat
        - more testing based, policy driven, dev workflow centric
        - doesn't reinvent the wheel, rather reacts to agentic disruption and responds dynamically and with a sense "we belong here" and very intentionally and for a long time to come
        - as much a workflow/methodology/framework as any particular application or technology
        - most programmers who do use ai tools like Cursor are still approaching it as the "sixth bullet point in their product roadmap," like Marc Andreessen said
        - even these AI first code editors are primarily SaaS tools, therefore technologies, rather than methodologies, and also they are bolting on to existing things like VS Code (6th bullet point example yet its easy to fool you as an AI first tool)
        - more people focused on the tooling than the workflows, and the workflow piece is what 70% of this is emerging to be about
        - might still do a bit of tinkering with github actions to see if we can do a PoC, but don't want to get too caught up in the trap of focusing too much on building a tool rather than a framework
        - framework first, tools emerge
        - how could we build a good tool for something we still don't fully understand yet?
        - those who understant this workflow will be the best tool builders and benefit from explaning its' widespread adoption which is bound to happen eventually
        - start ups will become the next big companies and that's when this will catch like wildfire
        - bonus: we don't need funding or a business plan
        - still want to look for really interesting ways to ourselves get feedback loops optimized while building this framework, and indeed documentation can still be produced this way, not just code. but entire frameworks.
        - team based, hoping others contribute and share interest, collaborate, share together with joy and excitement
    - the tech side 
        - cicd focused (agent applies code in cloud without approval, but must pass tests iterated on by developer)
        - while agent is busy working, instead of waiting dev is writing yaml, giving feedback in git commit messages, and this is used for the next iteration in a trace bullet manner
        - critical dev skills still utilized, including git branching and merging skills, communication ability, especially in teams, and writing skills especially
        - agents get feedback from ci cd tests (pass, fail, metadata, logging)
        - devs find it interesting to optimize things like token useage, and making the repo more modular and less token heavy
        - metrics: tokens per query, log lifecycle management (some logs more effective than others in providing useful feedback, and might create noise and more tokens at some point. dev must monitor this, and will enjoy several interesting problem solving challenges)
        - plenty of other challenges sure to emerge, completely unpredictably and organically
        - agents apply their own code in cicd

### modeling
IDEA: modeling the feedback loop of coding, committing, pushing, waiting for test results, and plugging test result logs into as as  **TURN BASED GAME**

# Notes on "Agentic AI Needs a Systems Theory"

## arXiv:2503.00237

"At the most granular level, an agent contains an internal [ACT - SENSE - ADAPT] loop."

### Interfaces

- AGENT-HUMAN interface
- AGENT-AGENT interface
- AGENT-ENVIRONMENT interface

### Capabilities & Attributes

Collective agency metrics of some kind rather than isolated vanity metrics like this model has this score (so what? its more powerful to stack tinier more cooperative models together and their total output is more than the sum of their parts - how to measure and optimize that is the question.

agentic AI development would benefit from a more holistic view (*arXiv:2403.00833, 2024b.*)

metacognition - as a natural byproduct of emergence. Rather than a model being single handedly responsible, the entire system emerging towards benefitcial as of yet well understood or described meta cognitive qualities seen as beneficial.

## Agentic AI Systems Theory (AAIST)

*A new as of yet undeveloped method for describing how agency at the system level can emerge from the interactions between much simpler agents (tool-use LLMs), humans and the environment.*

### Key Concepts

- Emergent capabilities arise from agent interactions rather than individual model performance
- Systems-level perspective is essential for understanding agentic AI behavior
- Metacognitive awareness develops through environment and multi-agent interactions
- Current AI development focuses too narrowly on individual model capabilities

### Implications for My Work

- Consider designing systems of specialized agents rather than relying on single powerful models
- Focus on interface design between agents, humans, and environments
- Develop metrics that capture emergent system properties rather than individual agent performance
- Explore mechanisms for enhanced agent cognition through interaction

# Emerging Techniques for AI-Driven Workflows

## Version-Controlled Instructions as First-Class Citizens

- Source controlling README.md or "special instructions" documents as first-class citizens in AI workflows
- Treating these documents as hyper-optimized context layers that evolve alongside the project
- Leveraging git version control to track the evolution of these instruction sets over time
- Character/token optimization: packing maximum value into limited context windows (8,000 characters)
- Hyper-tuning instructions to the specific user running these workflows

## The Snowball Effect in AI-Driven Development

- Each iteration compounds improvements from previous sessions, creating accelerating returns
- Output quality improves exponentially rather than linearly as the system learns from feedback
- User perspective evolves alongside the AI system, creating a virtuous cycle of improvement
- Tracer bullet workflow: rapid, continuous feedback that guides the development process
- Using software as a tester with joy rather than frustration

## Personal AI Enhancement Patterns

- Applying these techniques beyond code to enhance daily life:
  - Fitness routines with AI-optimized workout instructions
  - Fashion recommendations based on evolving personal style
  - Shopping assistance for targeted deals (e.g., Amazon sales)
- Personalized context that evolves with the user's needs and preferences

## Token Conservation Economics

- Optimizing the most valuable 8,000 tokens for each specific project
- Strategic pruning of instructions to maintain maximum relevance
- Measuring ROI on token usage across iterations
- Developing metrics for token efficiency and effectiveness
- Creating lightweight instruction sets that maximize AI performance while minimizing token consumption
- Tokens remain an expensive resource requiring careful management
- Exploring alternative SCM tools beyond git for more token-efficient diffs
- "Replay" capabilities for queries under different configurations to maximize token value

## Feedback Loop Optimization

- Structured feedback mechanisms that capture both explicit and implicit user responses
- Git commit messages as a feedback channel for AI systems
- Metadata collection and analysis to identify patterns in successful interactions
- Continuous refinement of the instruction-feedback-improvement cycle
- Measuring the delta between iterations to quantify improvement

## Unexpected Workflow Shifts

- Terminal-centric development replacing traditional code editors
- Increased time in environments like WSL, tmux, and command-line interfaces
- Disproportionate returns on optimizing terminal configurations vs IDE settings
- Keyboard-driven workflows becoming more valuable than GUI-based interactions
- Text-based interfaces proving more token-efficient than graphical representations
- Traditional git diff outputs becoming problematic due to token-intensive formatting
- Need for specialized tools optimized for AI-driven text document management
- Emergence of new bottlenecks that were non-issues in traditional development
