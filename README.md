## Contact
<i>Write as first word in your first message: GitHub</i>

[![Mail](https://img.shields.io/badge/Mail-simonwaiblinger@wobbit.at-07000C?style=rounded&logo=gmail&logoColor=DCBEFF&labelColor=1F1924)](mailto:simonwaiblinger@wobbit.at)

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=simwai&hide_progress=true&bg_color=07000C&text_color=DCBEFF&title_color=DCBEFF&border_color=DCBEFF" />

## About Me
I'm Simon Waiblinger (simwai, or Wobby to some), a full-stack developer working from Vorarlberg, Austria, who has spent the past five years building systems that prioritize reliability and velocity in roughly equal measure — though the balance shifts depending on whether I'm maintaining production systems under pressure or prototyping a new trading algorithm. My frontend work centers on Vue and Angular — Vue for its pragmatic approach, Angular for enterprise applications (especially with .NET backends) where sustained development investment justifies the framework's complexity. Backend work spans Node.js and .NET ecosystems.

Much of my work involves automation in its various manifestations: trading bots that execute strategies without human intervention, scrapers that extract signal from noise, and algorithms that compress complexity into manageable abstractions. I've also devoted substantial energy to building full-stack headless CMS platforms that decouple content management from presentation logic, allowing flexibility without the constraints of monolithic frameworks. Statistical analysis in Python rounds out the toolkit, transforming raw data streams into actionable insights through proper quantitative methods.

My architectural philosophy derives from pragmatic experience rather than dogmatic adherence to any single paradigm. Clean Code principles, the Law of Demeter, and strategies like KISS and DRY inform daily decision-making, while patterns like Observer, Strategy, Monad, Mixin, and Command provide structural scaffolding when complexity justifies abstraction. I favor explicit dependency injection over framework abstractions when transparency matters, composition over inheritance wherever feasible, and alignment with CUPID and SOLID principles as conceptual guides rather than rigid constraints. The Agile Manifesto's emphasis on working software over comprehensive documentation resonates, though I interpret this as "documentation follows understanding" rather than "skip documentation entirely".

System reliability demands attention to failure modes that many developers ignore. I build graceful shutdown mechanisms into every long-running process and implement fail-fast logic that exposes problems immediately rather than allowing them to propagate through layers of abstraction. Modern codebases suffer from two opposing pathologies: excessive exception throwing that drowns signal in noise, and silent fallbacks that swallow failures until debugging becomes archaeological excavation. The correct approach makes errors visible, actionable, and traceable without creating so much logging overhead that production systems become unreadable observability nightmares.

Regarding AI-assisted coding: I use LLMs extensively for boilerplate generation, simple markup, and repetitive structural work where variation adds no value. This is purely instrumental — there's no conceptual benefit to manually typing another form validation block when the pattern is already established. However, business logic, state management, and anything involving non-trivial complexity requires human cognition because debugging AI-generated code you don't fundamentally understand transforms development into superstitious cargo-culting.

The same principle applies to monorepo frameworks: Nx's power comes with operational complexity that creates knowledge silos and debugging challenges. I favor Turborepo's lighter approach when framework benefits justify the dependency, but custom PowerShell scripts often deliver better long-term maintainability. The calculus is simple: if losing one team member means nobody can fix your build pipeline, your architecture has a single point of failure. Architectural decisions should match team capacity and actual scale, not aspirational complexity.

My open-source contributions include a merged PR to npm-packlist that improves debugging output for 20+ million npm users, potentially saving thousands of developer-hours daily through better error visibility in the packaging pipeline. I authored the PowerShell deployment automation script for freqtrade (a trading bot with 30k+ GitHub stars) and implemented scheduled cooldown reset functionality that prevents strategy exhaustion during volatile market conditions.

Outside software development, I maintain balance through physical and contemplative practices. Taekwondo training builds kinesthetic awareness and focus, meditation practices (mudras, Qi Gong) develop body-mind integration, and gym work provides straightforward feedback loops between effort and result. Winter brings freeriding opportunities, vacations typically involve coastal environments, and I practice shuffle and hip-hop dance styles as creative outlets. Swimming serves both athletic and meditative purposes. Alpha wave music maintains flow states during extended coding sessions. Gallery visits, concerts, and social events provide exposure to perspectives outside the technical bubble, while family time, nature exposure and laughter keep me grounded in reality rather than pure abstraction.

I draw intellectual inspiration from Salvador Dalí's surrealist work, which demonstrates how constraint violation can reveal deeper structural truths, and from developers like sindresorhus (TypeScript craftsmanship) and xmatthias (Python technical depth) whose code exemplifies clarity without sacrificing power.

<br />
<kbd>
<img src="https://simonwaiblinger.de/mario-coding.gif" alt="Mario Coding" />
</kbd>
<br />
