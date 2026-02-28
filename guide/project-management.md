# basic project management

**Source:** [A developer's guide to project management (PM), Part 1/2]()

If you're a developer, you have worked on a project. No matter if it's a million-dollar CMS system or the website for your neighbor's farm store. Even that Todo-list you built by following a tutorial is, by definition, a project. Because it has some classic characteristics:  

-   It is **unique** (you might develop the app twofold but with different knowledge & constraints)
-   It has a **[SMART](https://en.wikipedia.org/wiki/SMART_criteria)** objective (the creation of a todo-app within the tutorial's scope)
-   It has a designated **team** (you)
-   It has a **budget, and a timeframe** and adheres to a certain **quality**

[![](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fpgxowbtm5zx4oit2q0rh.jpg#_uDarkloading=lazy&width=800&height=480&inside_clickable=true)](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fpgxowbtm5zx4oit2q0rh.jpg)

But this does not really feel like a **development** project. You're not creating something new but following laid-out instructions.

## [](#tutorials-are-not-really-projects)Tutorials are not (really) projects

If you follow a video or post, you don't need to think much about project management. Somebody already did most of it for you, such as

-   Choosing the appropriate topic, audience, and distribution channel
-   Creating a lineout of the topic, write the script/post & the code
-   Recording the video if necessary

What's left to do is _just_ recreate what the instructions say.

There are thousands, if not millions, of videos on software development on Youtube. But there is (probably) not a single tutorial on earth that can prepare you perfectly for your first project. Tools like Google, Stackoverflow, and YT tutorials help, but their usefulness stands in no proportion compared to proper project management.

Of course, you can build an abundance of projects by copy-pasting from the internet. It's been done before, not only for development. Perhaps at the end of the day, you would create a piece of work so self-explanatory that it'd be ridiculous to ask for specifications. Or docs. Or workflow charts.

## [](#a-project-must-be-comprehensible)A project must be comprehensible

It's late in the evening. You go to sleep. And wake up to your personal kingdom come.

> "Will the software break if I make this change? What have I done here? And why!?"

Think about much worse this will be for others. Like your teammates who see your assignment for the first time. Or the poor chap picking up the implementation after two years to make a small change. Which could be yourself.

If your successor does not understand your doings and your reasoning, there's bound to be trouble:

-   A new feature blocks an old one. A department which used it for years is irritated and loses its efficiency. Or your end users will be unhappy and complain about your app on social media.
-   A patch does not fix an error properly or introduces new technical debt
-   An old feature breaks. Worst case: Your client's company production comes to a standstill until the error is repaired

Before you even think about hitting the keys, you should take an appropriate amount of time to prepare.

## [](#choose-an-appropriate-pm-procedure)Choose an appropriate PM procedure.

Before you decide _what_ to do, you should decide on the _how_. A famous tool to support your decision-making here is the Stacey-Matrix. It helps you decide how to approach a new project.

[![](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fb2ntwpw4ehdhif3yutyj.png#_uDarkloading=lazy&width=535&height=428&inside_clickable=true)](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fb2ntwpw4ehdhif3yutyj.png)

If you trust the illustration above, every project can eventually be _simple_.

Given you're persistent enough with customer interviews and willing to learn a new technology before starting a project - you will probably run out of budget before even starting to write a single line of source code.

On the other hand, not every project is always meant to be agile. Agile projects aren't easier - quite the opposite. They can, however, prevent you from spending innumerable hours on preparation.

Once you've made your choice, write a line or two and **explain it**. Try and answer questions such as:

-   Why did you choose the agile approach over the waterfall one (or vice-versa)?
-   Are all obvious requirements known? Who knows about them?
-   Which of your project team members has the relevant domain knowledge?

## [](#write-down-the-requirements)Write down the requirements

A famous quote says `First solve the problem, then write the code`. But before you can solve a problem, you need to understand it. Even if you work on one of your weekend projects, you should have a rough idea of your final product.

> ⚠️ The results from this step have an immediate and long-lasting impact on the project's sustainability

I have noted down the four most common approaches to gathering information below. They work independently of the chosen PM method.

And no matter which of the methods you choose, always keep this in mind:

> ❗ **Write Everything Down and Keep Your Notes Organized**
> 
> If you are looking for tooling, give [Obsidian](https://obsidian.md/) and its [Dataview-plugin](https://github.com/blacksmithgu/obsidian-dataview) a try. There's a template I use you can find in this [Github Repos](https://github.com/tq-bit/project-planning-resources/blob/main/assets/templates/functional-specification.md).

## [](#analyze-existing-systems)Analyze existing systems

If the result of a previous project is already installed, you might not need to reinvent the wheel. Sometimes, it's enough to look at legacy project artifacts to understand the problem. Reading through a few lines of documentation can occasionally be more efficient than exchanging a thousand words with domain experts.

### [](#when-analyzing-existing-systems-do-this)✅ When analyzing existing systems, do this:

-   If there's no **documentation**, **create** one for yourself
-   **Ask** who was **responsible** for the system's **implementation** in the past
-   **Create** a **local project** you can test out and take for a ride
-   Try and **understand the reasoning** behind the implementation
-   **Understand** the **business process** the system supports

### [](#when-analyzing-existing-systems-avoid-this)❌ When analyzing existing systems, **avoid** this:

-   Introduce any kind of changes to the original source code
-   Make vague assumptions about implementation details

## [](#hold-1on1-1on2-interviews)Hold 1-on-1 / 1-on-2 interviews

More often than not, you will need further intel from your customer. Especially if you're dealing with a smaller, owner-run business.

There are a few things to remember when preparing for these interviews. First and foremost: **Assume that your client doesn't know (much) about technology.**

> 💡 **This also counts for yourself**.
> 
> If you're planning a side project and ask yourself what you want, be honest with yourself about your domain knowledge.

After the initial interview, you might have to meet up with other department experts and stakeholders. Make sure to attend each meeting with questions and a clear goal of what information you want to get out of it.

### [](#in-1on1-interviews-do-this)✅ In 1-on-1 interviews, do this:

-   Ask **open questions**
-   Write **a protocol** and send it to your client after the interview
-   **Note** down **domain knowledge** and **stakeholder** names
-   Use your experience and **nudge your client** in the right direction
-   Keep **eye contact**. Be nice. Make your client feel heard and understood

### [](#in-1on1-interviews-avoid-this)❌ In 1-on-1 interviews, avoid this:

-   Ask manipulative questions
-   Speak only in technical terms
-   Do all the talking on your own
-   Use hasty and intrusive body language
-   Give in to external distractions, such as your mobile device.

## [](#hold-workshops)Hold workshops

In large projects with an enterprise-wide effect, it's essential to consider a variety of demands. Each department has different requirements, some of which might conflict and must be discussed internally.

> ⚠️ **Don't neglect corporate politics.**
> 
> People who support your project can vastly improve the general acceptance of your project. The same is true the other way around.

Workshop meetings bind a lot of people. They must be planned and moderated appropriately to yield acceptable results and should be held right at the beginning of a new project. Their results should also be communicated to stakeholders who were not part of the meeting.

> ℹ️ Classic workshops in agile projects are often extended by Sprint Artifacts. I've tried to phrase the following dos and donts so they can be applied on both occasions.

### [](#in-workshop-meetings-do-this)✅ In workshop meetings, do this:

-   **Invite key users** from all involved **departments**
-   **Prepare** a meticulous **agenda** and **time-box every topic**
-   **Plan** a total of 25-30% **time** **buffer for discussions**
-   **Plan** **10 minute-breaks** for every **90 minutes of work**
-   If a **discussion goes off-topic**, ask the participants to **schedule a follow-up meeting**

### [](#in-workshop-meetings-avoid-this)❌ In workshop meetings, avoid this:

-   Permit unmoderated back-and-forths
-   Give [Energy vampires](https://en.wikipedia.org/wiki/Psychic_vampire) a stage
-   Hold online meetings, if possible\*
-   Allow meetings-in-a-meeting\*\*
-   Skipping lunch\*\*\*

\* at the beginning of a project, shaking hands builds stronger bridges than playing online icebreaker games

\*\* smaller groups of people discussing a particular topic among themselves

\*\*\* not only will it give people time to mentally recover, but it also gives them a chance to informally connect with each other

## [](#construct-a-timeframe)Construct a timeframe

So far, we've chosen a PM method and gathered the client's requirements. You should now be able to make an educated guess on the time frame. The actual time frame, not the one you sold to win the pitch.

-   For waterfall projects, you can use tools like the [Critical Path Method](https://en.wikipedia.org/wiki/Critical_path_method) or a [Gantt chart](https://en.wikipedia.org/wiki/Gantt_chart) to outline the project's milestones
-   In agile projects, you should be able to estimate the delivery date and tasks of the first [sprint-increment](https://en.wikipedia.org/wiki/Scrum_(software_development)#Sprint)

> ℹ️ If you're using a markdown tool that supports Mermaid.js, you can easily make the time frame part of your project notes. Example: [See this template](https://github.com/tq-bit/project-planning-resources/blob/main/assets/templates/functional-specification.md#planning-phase)

## [](#gather-feedback-and-learn)Gather feedback and learn

Now is the perfect time for a feedback loop. Discuss the requirements in smaller rounds. Once with your client, once within your team (or give yourself time to reflect on it). If necessary, run smaller 1-on-1 interviews with participants of the workshop again.

In a perfect world, you would eventually have all information you need to start developing. Nobody would bother you again. You can bury yourself in your dev cave to get something on the road.

That won't happen. No matter the size, projects are bound to alter as they go.

And Rarely is there a chance to learn so much in such a small timeframe than last-minute requirement changes! The most prominent chunk of your **lessons learned** stem from here.

> 💡 Remember the experience I mentioned in '1-on-1 Interviews'? Here is where you get it

Be aware that you don't have to sign off every late riser's _nice-to-have_ request. Make a note or ticket, place it under v2.0.0, and check in if it will still be a problem after the initial release.

## [](#recap-amp-outlook)Recap & Outlook

You probably haven't written a single line of code yet. Which is good. That means that you took care to understand your client's problem and are capable of offering an appropriate solution.

You might also have a collection of several documents, such as

-   An agreed-upon PM-procedure
-   Meeting notes and workshop protocols
-   Flowcharts for current business processes
-   A dossier of stakeholders and interested parties
-   A timeline or an outline for the first sprint

You've also gotten to know how your client and his business operations. Thereby laying a solid foundation on which you can start development.

The subsequent article will outline inter-team communication. You will also learn how to create a solution proposal and implement it. Finally, it will provide you with a set of methods and tools which you can use for your everyday project management business.