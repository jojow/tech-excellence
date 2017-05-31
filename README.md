We often try to get better by following the latest tech trends such as microservices, serverless and the like.
These are mostly technical efforts to improve.
However, what often makes the key difference is:

# Technical Excellence

A great entry point is the follwing 30mins talk by Martin Fowler:

https://www.youtube.com/watch?v=Avs70dZ3Vlk

He points out pretty clearly the key aspects of building and maintaining an organization that aims for technical excellence in the long run:

## [What does tech excellence look like?](https://www.youtube.com/watch?v=Avs70dZ3Vlk) by Martin Fowler
"Having technical excellence in your organisation has never been as crucial as it is today. Creating a technology strategy that allows you to not only deal with, but take advantage of the increasingly rapid pace of change separates the successful organisations from the obsolete ones.
How do we ensure we attract and keep the right talent that can create and execute sophisticated strategies, in the face of extreme competition?
Martin explores how culture, structures, talent, and technology choices help to build organisations that have technical excellence ingrained in them."
* **Improve IT performance**
  * Reduce cycle time (i.e. frequent and fast deployments)
  * Focus on reducing mean time to repair (MTTR) instead of mean time between failure (MTBF)
* **Do continuous delivery**
  * Version control
  * Continuous integration
  * Test automation
  * Deployment automation
* **Carefully structure your teams**
  * You cannot avoid silos, humans will always form silos
    * However, you can control the borders of these silos, so they support your business
  * A team must be small, business-oriented, and autonomous
  * Teams should be as long-term and stable as possible
* **Establish trustful environment**
  * Ask for help
  * Share knowledge
  * Learning > Blame
  * Home for the evening
  * No toxic people
  * Integrity
* **Led by technology**
  * Peer recognition > Manager recognition
  * Value technical skill (to same degree as other skills like management etc.)
  * Continuous learning
  * Engage with technology community
  * No golf-course purchases
* **Focus on getting excellent in your strategic software (competitive advantage)**, not utility (payroll, HR)
  * Technical excellence is important in general, but you must prioritize because your resources are limited

### Efficient collaboration between software development and business

![Efficient collaboration between software development and business by Martin Fowler](business-tech-excellence-by-martinfowler.png)

----

More stuff on roles, management vs. technical and more:

## [The architect elevator - visiting the upper floors](https://martinfowler.com/articles/architect-elevator.html) by Gregor Hohpe
"Many large organizations see their IT engine separated by many floors from the executive penthouse, which also separates business and digital strategy from the vital work of carrying it out.
The primary role of an architect is to ride the elevators between the penthouse and engine room, stopping wherever is needed to support these digital efforts: automating software manufacturing, minimizing up-front decision making, and influencing the organization alongside technology evolution."
* Traditionally, architects were considered to be those folks who make major design decisions on a project, draw architecture diagrams, and direct developers. Those tasks are in fact **better handled by the development team and modern tooling** than by a single person.
* Many modern companies therefore **eschew software architect as a separate job title**, even though they highly value software architecture.
* The good news is that **many new tasks await architects in large organizations.** And they are far more interesting and impactful than drawing class diagrams.
* Countless layers of management separate the upper floors from the lower ones. ... telephone game effect: when a message passes through many stations, it not only takes time, but its meaning can also be completely changed.
* As organizations are unlikely to collapse their management layers anytime soon ... architects need to move quickly between the floors to align business strategy with IT architecture and technical implementation. An elevator ride from the engine room up to the penthouse
* Modern architects must therefore be well-versed in run-time architecture considerations, including deployment and configuration automation, scalability, monitoring, etc. They may **trade class diagrams for deployment diagrams!**
* Modern architects should not just look at the design, but also the "manufacturing" [continuous delivery etc.] of software. Improving this aspect of the engine room has a critical impact on the penthouse: rapid and repeatable delivery shortens the time it takes for software to deliver business value. A great reason to visit the upper floors.
* To improve effectiveness in the IT engine room, you may have to change how the organization functions. That’s why architects must ride the elevator to the upper floors.
  * Minimize up-front decision making ... architecting an application to be horizontally scalable and automating server provisioning allow the sizing decision to be deferred until production or load-testing time
* **Architecture is selling options.** Companies should invest more in architecture that allows them to defer decisions. Now this is the type of conversation an architect wants to have in the upper floors of his or her organization!
* TODO

## [The engineer/manager pendulum](https://charity.wtf/2017/05/11/the-engineer-manager-pendulum/) by Charity Majors, tweets by Sarah Mei
* Drop the idea that only managers get career progression.
* Drop the idea you have to choose a "lane" and grow old there.
* The best individual contributors are the ones who have done time in management.
* **The best technical leaders in the world are often the ones who do both (technical and management).** Back and forth. Like a pendulum.
* There are lots of people who do both well - **but serially. Not simultaneously.**
* ... **hybrid manager+tech lead. This is an unstable combination,** because your engineering skills and context-sharpness are decaying the longer you do it.
* You can only really improve at one of these things at a time: engineering or management.
* Management is highly interruptive, and great engineering - where you're learning things - requires blocking out interruptions. You can't do these two opposite things at once. As a manager, it is your job to be available for your team, to be interrupted. It is your job to choose to hand off the challenging assignments, so that your engineers can get better at engineering.
* A tech lead is a manager ... but their first priority is achieving the task at hand, not grooming and minding the humans who work on it. They still need the full manager toolset. ... management work, from the slightly shifted perspective of "Get Thing X Done" not "care for these people".
* **Management is not a promotion, management is a change of profession.**
* Becoming a manager is not a promotion - it's a lateral move onto a parallel track. You're back at junior level in many key skills.
* ... it leads to so many people managing even though they hate managing and have no business managing, and also starves the senior eng pool of the great mentors and elder wizards we need.
* Do [management] as long as it makes you happy, and the people around you happy. Then stop. Go back to building things.
