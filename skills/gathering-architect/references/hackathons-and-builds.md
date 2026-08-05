# Intensive Collaborative Events

## Hackathons, Unconferences, and Design Sprints

Reference for designing and running intensive collaborative events that bring people together to create, learn, and innovate at scale.

> **Pointers to other files**:
> - **Open Space Technology** (the underlying facilitation method): `facilitation-methods.md`. Unconferences are an event format that applies Open Space; the canonical method treatment is in the methods file.
> - **Workshop design for hands-on learning** (build sessions, pair/mob programming, show & tell): `facilitation-methods.md`.

---

## Table of Contents

1. [Hackathon Design & Execution](#hackathon-design--execution)
2. [Unconferences & Open Space Technology](#unconferences--open-space-technology)
3. [Design Sprints](#design-sprints)
4. [Cross-Format Principles](#cross-format-principles)
5. [Virtual & Hybrid Considerations](#virtual--hybrid-considerations)
6. [Sources & Further Reading](#sources--further-reading)

---

## HACKATHON DESIGN & EXECUTION

Hackathons are intensive, typically 24-72 hour events where teams collaborate to solve problems, build projects, and innovate under time constraints. The core format has evolved significantly, with modern hackathons now emphasizing learning, community, and diverse participation over purely competitive outcomes.

### Core Hackathon Philosophy

**Foundation**: Hackathons prioritize rapid problem-solving, team-based collaboration, and building functional prototypes under intense time constraints. Unlike workshops (which teach skills through structured curricula), hackathons emphasize self-directed and peer-driven learning through doing and iterating quickly.

**Key Value Proposition**: Hackathons are a sandbox for bold ideas, attracting self-driven individuals capable of rapid development who value learning over profit and creative problem-solving over startup development.

---

### Planning Runway

Major League Hacking publishes a thorough organizer guide with a full planning calendar, and it is the best free resource on this: https://guide.mlh.io/. Their timeline is theirs and is not restated here. What follows is the shape of the problem and the ordering we would hold onto.

Give yourself months rather than weeks. The two things that take longest, money and people, are the two that cannot be rushed at the end. Sponsors have their own decision cycles and need something to say yes to. Participants need enough notice to clear a weekend and find people to build with.

The ordering matters more than the dates:

- **What gates everything else comes first:** the date, the venue, and a short honest answer to why this event exists at all. Every later decision is a consequence of those three, so making them late means remaking everything.
- **Money next**, because the budget sets the size of the event and the size changes every other choice. Work out what you need before you promise anyone anything.
- **Then the audience.** Open registration once the page can answer what someone actually gets out of turning up, not before. An early page with nothing on it spends attention you only get once.
- **Then the machinery participants will meet on the day:** how judging works, how mentors get found, what people eat, where they ask questions. This is the part first-time organizers underestimate, and it is the part attendees experience most directly.
- **The final month is rehearsal, not design.** Numbers get confirmed, materials get made, the run of show gets written down. If you are still designing the event a month out, something needs cutting.
- **The last week is logistics only.** Reminders, setup, safety, a walkthrough with the team.

Afterwards, do the four things almost everyone skips: thank people properly, ask them what actually happened, tell sponsors what they bought in terms they care about, and publish what got built so the work outlives the weekend.

### Event Duration & Timing Flexibility

- **Minimum**: 24 hours (overnight venue required)
- **Standard**: 36-48 hours (weekend format)
- **Extended**: 72 hours for larger events
- **Preparation window**: 4-6 weeks minimum for team formation, idea exploration, and proper organization

### Venue & Logistics Requirements

**Venue Essentials**:
- Must be available for overnight stay (participants sleep on-site for 24+ hour events)
- Adequate table and seating for team work areas
- Good WiFi and power infrastructure
- Space for presentation area and judging stations
- Designated mentorship area

**Participant Support**:
- Sufficient on-site food to feed all attendees (multiple meals for multi-day events)
- Healthy food options and clear dietary accommodation options
- Beverages and snacks throughout the event
- Sleep areas and designated quiet zones
- Restrooms and shower facilities (for extended events)

---

### Team Formation Strategies

#### Formation Timing & Structure

- Teams typically form around ideas presented at the event
- **Minimum team size**: 3 members (no solo participants)
- **Ideal team size**: 3-5 members for efficient collaboration and accountability
- **Maximum team size**: Keep similar across all teams for fairness in judging

#### Skill Diversity Framework

Diverse teams outperform homogeneous teams. Strong teams include members with complementary skill sets:

**Essential skill mix**:
- Front-end development or design
- Back-end development or system architecture
- Project management or coordination
- Business/strategy thinking

**Types of diversity to prioritize**:
- Technical skill diversity (designers, developers, DevOps, etc.)
- Experience level (experienced + first-time hackers)
- Domain expertise (if theme-specific)
- Demographic diversity for inclusion and innovation

#### Team Formation Methods

**Open Selection** (most common):
1. Participants pitch ideas in a time-boxed session (2-3 min per pitch)
2. Interested hackers gather around pitch facilitators
3. Teams form organically through conversation and negotiation
4. Organizers ensure all participants are assigned to teams

**Assisted Matching**:
- Organizers use skill surveys to suggest team combinations
- AI/algorithm tools can facilitate diverse team formation
- Mentors help identify struggling individuals and facilitate team joining

**Facilitator Role**: Ensure no one is left without a team; be prepared to help individuals join teams or reassign members if necessary.

---

### Mentorship Structure & Office Hours

Mentorship is a critical success factor that improves project completion rates and team confidence.

#### Mentor Recruitment

**Target profiles**:
- Existing tutors or teaching assistants
- Alumni from organizing school/organization
- Industry professionals and guest experts
- Senior participants from previous hackathons
- Faculty members

**Recruitment process**:
- Create dedicated mentor recruitment page
- Provide registration form where mentors select available time slots
- Communicate clear expectations and guidelines

#### Mentor Guidelines & Training

Provide all mentors with a guide addressing:
- Appropriate questions to pose (guiding vs. solving)
- Troubleshooting methodologies and frameworks
- Curated beginner resources for common challenges
- Escalation procedures for critical issues

#### Mentorship Delivery Models

**Time Slot System**:
- Assign specific mentorship time slots (e.g., "3pm-4pm")
- Encourage mentors to be present throughout event
- Create schedule visibility for hackers

**Always-Available Model**:
- Mentors present throughout event
- Hackers can approach mentors as needed
- Works best with dedicated mentor area

**Hybrid Approach** (recommended):
- Mentors have assigned "office hours" (scheduled availability)
- Mentors encouraged to visit hacking areas spontaneously
- Dedicated physical mentorship zone for drop-in help
- Digital mentorship channel (#mentorship on Slack/Discord)

#### Support Infrastructure

**Communication channels**:
- Dedicated mentorship channel on Slack/Discord
- Physical mentorship area with visible signage
- @mentor role for easy identification
- Voice/video chat for remote support (hybrid events)

**Mentor Activities**:
- Organizers actively monitor chat and identify struggling teams
- Facilitate introductions between hackers and relevant mentors
- Mentors maintain responsiveness and presence
- Regular "mentorship office hours" for group Q&A sessions
- Mentors visit hacking spaces directly (don't wait passively)

---

### Judging System Design

Judging is the most under-planned part of most hackathons and the part participants remember longest, because it is where the event tells people whether their weekend counted. Major League Hacking's organizer guide covers judging mechanics in detail and is worth reading before you design yours: https://guide.mlh.io/. The guidance below is our own, and it is about the decisions rather than the procedure.

**Decide first whether teams come to the judges or the judges come to the teams.** Judges walking a room of tables, seeing everything, is the fairer arrangement and the easier one to run: nobody is ranked against a subset of the field they happened to share a room with, teams stay with their work, and a demo that breaks can be shown rather than described. Stage pitches produce a better spectacle and a worse result, because they quietly reward presentation skill over what got built. If you want the ceremony, run the pitches for the finalists after the judging, not as the judging.

**Weight what was made, not how it was sold.** A rubric that leans on pitch quality selects for confidence, which correlates with prior experience, which is the opposite of what most hackathons say they are for. Pick a small number of dimensions, tell teams what they are before the event starts, and keep the list short enough that judges can hold it in their heads while walking a room.

**Work out how many judges you need before you promise a judging window.** The arithmetic is simple and unforgiving:

```
judges needed = (projects × rounds per project × minutes per project) / minutes of judging time
```

Three rounds per project and a few minutes each is a reasonable starting point, and rounding up is always correct. Do this sum early, because the answer is usually "more judges than you have invited" and judges take weeks to recruit. This formula and the recommendation to see each project more than once both come from MLH's guide, linked above.

**Normalize across judges rather than trusting their scores.** Judges score on wildly different scales, and averaging harsh and generous scorers together mostly measures who happened to see whom. Asking each judge for a short ranked list instead of absolute numbers, then aggregating the rankings, removes most of that noise for very little extra effort.

**Protect the time limit and say so in advance.** A firm few minutes per team, announced beforehand and held to on the day, is what makes the process fair. Teams plan for the limit they are told about, so changing it mid-event penalizes the ones who believed you.

**Give judges a backup and a fallback.** Ask for a short demo video at submission. It gives judges something to review during deliberation, and it saves any team whose laptop chooses the worst possible moment.

**Keep the room informed while you deliberate.** Silence after demos reads as chaos. Say roughly how far along judging is and when results are coming, and put something on for people to do while they wait.

### Mini-Events & Energy Management

Multi-day hackathons require active energy management. Mini-events provide breaks, excitement, and engagement while maintaining momentum.

#### Purpose & Principles

- Give hackers breaks from intensive building
- Add variety and fun to the experience
- Maintain community energy and excitement
- Prevent fatigue and burnout
- Create memorable experiences and informal bonding

#### Event Categories & Ideas

**Gaming Tournaments**:
- Multiplayer games (League of Legends, Rocket League, Smash)
- Jackbox party games (excellent for inclusivity—only one person needs to own it)
- Chess or Minecraft servers
- Esports viewing/competitive streaming
- Typing contests (10FastFingers)
- Trivia tournaments (honor system for remote)

**Creative & Design Challenges**:
- Code-in-the-dark (5 minutes to recreate a website, judges vote favorites)
- MS Paint art competitions
- Skribbl.io or drawing games
- Rapid prototyping challenges
- Design mockup contests
- Show & tell sessions (hackers present their current work)

**Social & Wellness Activities**:
- Slideshow karaoke (random presentations without preparation)
- Hourly conversation prompts and icebreakers
- Music voting/DJ activities
- Group stretching and calisthenics
- Active breaks with movement

**Logistics**:
- Stream at no higher than 720p @ 30fps to avoid network strain
- Use ethernet connections when possible
- Test technical setup before broadcast
- Schedule mini-events at regular intervals (every 4-6 hours)
- Ensure activities are optional and inclusive

#### Team Involvement

- Involve your organizing team in running mini-events
- Let team members lead their favorite activities
- Serves as team-building before event
- Builds investment in event success

#### Audience Consideration

Remember: not all hackers are gamers or extroverts. Provide variety in:
- Competitive vs. collaborative activities
- Screen-based vs. physical activities
- Solo vs. group participation
- High-energy vs. relaxing options

---

### Workshops During Hackathons

Workshops provide skill-building and inspiration during the event, helping teams overcome challenges and learn new tools.

#### Workshop Planning

**Timing**:
- Schedule in gaps between team formation and final push
- Typically 30-90 minutes per workshop
- Morning and early evening slots work well
- Avoid late-night workshops (people sleep)

**Topics**:
- Tool walkthroughs (APIs, frameworks, libraries)
- Design thinking and brainstorming
- Beginner tutorials for common languages/frameworks
- Domain-specific deep dives (ML, blockchain, AR, etc.)
- Soft skills (pitching, collaboration, project management)

**Format**:
- Keep talks short and demo-heavy (40% demo, 60% talking)
- Provide code examples and starter templates
- Encourage Q&A and hands-on practice
- Record sessions for asynchronous access

**Delivery**:
- Have workshops delivered by mentors or sponsors
- Provide video recording for those who can't attend
- Share slides and resources in advance
- Have backup instructors in case of no-shows

---

### Virtual vs. In-Person vs. Hybrid Hackathons

Modern hackathons exist across the participation spectrum. Each format has distinct design considerations.

#### In-Person Hackathons

**Advantages**:
- Rich informal interactions and spontaneous collaboration
- Easy team formation and socialization
- Direct mentorship and immediate support
- Shared physical energy and momentum
- Strong community bonding

**Design focus**:
- Comfortable venue with good WiFi
- Intentional social spaces (not just tables)
- Easy mentor access and visibility
- Clear signage and wayfinding
- Comfortable sleep areas for overnight events

#### Virtual Hackathons

**Advantages**:
- Global reach and accessibility
- No travel requirements
- Inclusive for people with mobility or caregiving constraints
- Time zone flexibility (asynchronous options)
- Lower cost to organize and participate

**Design challenges**:
- Maintain engagement and community feeling
- Support team formation across distances
- Provide effective mentorship remotely
- Manage time zones

**Virtual-specific requirements**:
- Video meeting platform (Zoom, Google Meet)
- Shared collaboration tools (Miro, Google Jamboard, Figma)
- Project management tools (Asana, Trello)
- Slack/Discord for communication
- Shared code repositories (GitHub)
- Async communication for time zones
- Clear participation guidelines and expectations

#### Hybrid Hackathons

**Design challenges**:
- **Asymmetry problem**: Co-located participants have natural advantages (informal conversations, shared artifacts, peripheral awareness)
- **Equity**: Remote members receive unequal access to mentorship, feedback, and recognition
- **Communication complexity**: Integrating multiple platforms and participation modes

**Hybrid-specific design requirements**:

1. **Equal visibility and support**:
   - Remote participants get same mentorship access as on-site
   - Mentors split time between in-person and video sessions
   - Judges evaluate remote projects fairly (video submissions help)
   - Recognition given equally to remote and on-site teams

2. **Structured participation scaffolding**:
   - Daily check-ins with all teams (video call)
   - Scheduled mentorship rotations (both formats)
   - Clear participation guidelines in advance
   - Shared rituals (opening, closing, mid-point celebration)

3. **Technical infrastructure**:
   - Reliable video streaming for remote participants
   - Real-time document sharing (shared workspace)
   - Livestreamed key moments
   - Backup communication channels if platforms fail
   - Context-aware features (session times in participant's timezone)

4. **Bridging activities**:
   - Informal "drop-by" sessions for remote participants
   - Pair on-site and remote mentors for teams
   - Shared online workspace for all collaboration
   - Intentional remote introductions during team formation

5. **Platform excellence**:
   - Streamlined registration and profile management
   - Easy venue and room information access
   - Clear participant experience guidelines
   - Accessibility considerations (captions, audio descriptions)

**Key insight**: The success of hybrid events depends on intentional design to eliminate asymmetries, not treating remote and in-person as equally easy.

---

## UNCONFERENCES & OPEN SPACE TECHNOLOGY

Unconferences are participant-driven events where attendees design the agenda. Open Space Technology (OST), developed by Harrison Owen in the mid-1980s, is the most common framework, and it has been run widely around the world ever since.

> **The method itself lives in `facilitation-methods.md`**, where it is described and pointed at Harrison Owen's own materials rather than restated. This section covers what is unconference-specific: when this event format works, how to get people actually moving between sessions in practice, and the BarCamp variant.

### When Unconferences Work Best

**Ideal conditions**:
- Diverse group with varied expertise
- Complex topic requiring multiple perspectives
- Time constraint makes pre-planning difficult
- Participants are self-motivated and prepared
- Community values emergence and self-organization
- Psychological safety exists for authentic sharing

**Less suitable for**:
- Brand-new audiences (need more structure initially)
- Highly regulated or hierarchical cultures
- Topics requiring linear progression
- Groups with significant power imbalances
- Participants expecting expert instruction

---

### Getting People to Actually Move

Open Space depends on participants leaving a session that isn't working for them and going somewhere better. Harrison Owen's own materials state the principle that permits this, and they state it well, so read it there. What follows is the practical problem nobody warns you about: telling a room they're free to move and getting them to actually do it are two very different things.

**Why people stay put even when you've told them not to:**
- In a small room, walking out is visible and feels rude
- Leaving your manager's session carries a cost that no announcement removes
- People new to the format read movement as a judgement on the convener
- Politeness norms are stronger than any framing you give in the opening

**What actually helps:**

1. **Say it before the day, not just on the day.** Put it in the invitation, so people arrive already expecting to move rather than hearing a surprising instruction in the opening circle.

2. **Model it yourself, visibly, in the first session block.** Get up and leave one. Come back to another. One facilitator doing this early does more than three reminders.

3. **Name the cost out loud.** "Someone leaving your session is not a verdict on you, and it's going to happen to me today too." Conveners who expect it take it far better.

4. **Design the room against the awkwardness.** Enough concurrent sessions that movement is constant background traffic, and enough physical space that leaving doesn't mean squeezing past six people.

5. **Watch the power dynamics and intervene quietly.** If a senior person's session is full of people who look trapped, go and pull two of them out yourself on a pretext. Once movement starts, it continues.

**The underlying point:** you're not enforcing a rule. You're making it socially cheap to do the thing the format needs, and that is a design job rather than an announcement job.

---

### Related Formats: BarCamp

BarCamp is an open unconference tradition that began in Palo Alto in 2005 as a community-run answer to an invitation-only gathering, and it spread because the people who started it deliberately left the name and the shape free for anyone to pick up. It is a tradition rather than a product. There is no owning organisation, no certification and no canonical script, and what any particular BarCamp does is decided by the people who turn up to run it. If you are considering one, read how the community itself describes it rather than working from anyone's summary.

- BarCamp community wiki: https://barcamp.org
- Background and history: https://en.wikipedia.org/wiki/BarCamp

---

## DESIGN SPRINTS

A design sprint is a time-boxed run at one big product question, where a small team goes from framing the problem to putting something in front of real people inside a single short stretch of calendar time. The point is to buy the answer cheaply, before anyone commits budget to building the thing for real.

The format was developed at Google Ventures by Jake Knapp and colleagues, and it is published in full, with its own day structure, roles, exercises and timings, in their book and on their own sites. None of that is restated here. If you want to run a design sprint, run theirs, in their words.

- The Design Sprint, Google Ventures: https://www.gv.com/sprint/
- The Sprint Book, by Jake Knapp with John Zeratsky and Braden Kowitz: https://www.thesprintbook.com/the-design-sprint
- Design Sprint Kit, Google: https://designsprintkit.withgoogle.com/

What this skill adds is the question that comes before the method: whether a sprint shape is right for the event you are actually hosting. Sprints and hackathons look similar from the outside, and they want very different things from a room.

### When a sprint shape fits a build event

A sprint shape earns its place when all of these are true:

- **There is one question, and the room agrees on what it is.** Sprints converge on an answer. Hackathons diverge into projects. A room carrying five unrelated ideas will not converge no matter how well you facilitate, and forcing it will just make four of the five feel unwelcome.
- **Somebody present can actually decide.** The convergence only happens because a real decision gets made partway through. If the person with that authority is not in the room for the whole thing, you are running a workshop that produces a recommendation, which is a fine thing to run but a different thing to promise.
- **You can put the work in front of real users.** The test is the payoff. Without it you have a well-facilitated opinion, and the team will trust it more than it deserves precisely because the process felt rigorous.
- **The same people can stay for the whole run.** Sprints are built on continuity of context. A rotating cast pays for the missing context out of the shared time, over and over.

A sprint shape is the wrong choice when the learning is the point rather than the answer, when people came to build the thing they personally care about, or when the group is large. Sprints are small-room formats. If you have forty people and one question, you want a facilitated large-group method instead, and the methods file has several.

### What to settle before you commit

Decide these five things before you put a sprint on anyone's calendar, because each of them is expensive to discover halfway through:

1. **The question, written down in one sentence.** If two people in the room would write it differently, you are not ready yet, and the writing is the cheap part.
2. **Who decides, by name.** Not a committee, not a role, a person. Tell them in advance that this is the job, so it is not a surprise on the day.
3. **Where the users come from.** Recruiting is the step that quietly sinks sprints. Book the participants before you book the room.
4. **What a "no" would look like.** Agree in advance what result would make the team stop, not just what would make them proceed. A process that can only say yes is a rehearsal, not a test.
5. **Who owns whatever comes out of it, the Monday after.** Sprint output with no owner decays faster than almost any other artefact a gathering can produce.

If you cannot answer all five, the honest recommendation is usually to run something shorter and looser first, get the question sharp, and sprint later with a room that knows what it is asking.

### What a rough build can actually teach you

A prototype is an argument made physical so that somebody outside the team can disagree with it. That is the whole of its job, and it is why the question worth asking before you build is not how much to build but which belief you are putting at risk. A team that cannot name the belief keeps building until the thing looks finished, because finished is the only stopping rule left to them.

Most builds that teach nothing were shown to a room that could not have been surprised. Colleagues, friends of the team and the person who first suggested the idea will give you warmth and no information. The people worth watching are the ones with somewhere else to go, and what you are watching for is whether the thing changed what they would do next, not whether they said something kind about it.

Decide before you show it what would count as a no, and say it out loud to the team. Testing has a way of producing encouraging noise, and a group that has not agreed in advance what disappointment would look like will find some in almost any set of reactions. Write down the response that would stop you, and if it turns up, report it first.

---

## CROSS-FORMAT PRINCIPLES

Several principles apply across all intensive collaborative event formats.

### Facilitator Excellence

Strong facilitation is the backbone of any intensive event. Facilitators create psychological safety, maintain momentum, and maximize participation.

#### Core Facilitator Responsibilities

1. **Environment creation**
   - Set up physical or digital space for collaboration
   - Establish psychological safety norms
   - Make space welcoming and inclusive
   - Provide necessary tools and resources

2. **Agenda and pacing**
   - Set clear timeline and milestones
   - Keep event on schedule
   - Adjust pacing based on energy and progress
   - Create space for breaks and informal time

3. **Participation management**
   - Invite quieter voices to contribute
   - Manage dominant speakers
   - Ensure everyone has opportunity
   - Make space for different participation styles

4. **Problem resolution**
   - Identify struggling teams or individuals
   - Provide support and resources
   - Resolve interpersonal conflicts
   - Escalate serious issues appropriately

5. **Energy management**
   - Watch for fatigue and momentum drops
   - Inject energy when needed (activities, breaks, celebration)
   - Celebrate wins and progress
   - Maintain positive, encouraging tone

#### Facilitator Presence & Visibility

- Be present and available throughout event
- Make yourself visible and approachable
- Check in regularly with participants
- Listen more than talk
- Be genuinely interested in people's experience
- Model the culture you want to create

---

### Icebreakers & Energizers

Intensive events benefit from structured activities that build connection and maintain energy.

#### Purpose & Timing

**Icebreakers** (beginning, 10-20 min):
- Warm up the group
- Get people participating and sharing
- Build initial connections
- Set tone for collaboration

**Energizers** (mid-event, 5-15 min):
- Refresh energy after intense focus
- Physical activity or mental break
- Quick, fun, inclusive
- Get people moving or laughing

#### Effective Icebreaker Activities

**Low-pressure options**:
- Speed networking (rotate partner every 3 min)
- Common ground (find something you share with someone new)
- Question cards (answer random interesting question)

Skip the ones the room has already done a hundred times, two truths and a lie in particular. `facilitator-pain-points.md` covers why a familiar icebreaker with no connection to the session lands worse than no icebreaker at all.

**Creative options**:
- Sketchpad challenge (draw something in 2 minutes)
- Show an object and tell its story
- "Highs and lows" from your week
- Best failure story (reframe as learning)

**Consider group size**:
- Small groups (under 10): intimate sharing activities work
- Large groups (30+): structured, fast-paced games work better
- Avoid awkward eye contact or being put on spot in large groups

#### Team-Building Principles

- Emphasize mixing groups (prevent cliques)
- Create space for all personality types (not just extroverts)
- Avoid forced fun (respect people's preferences)
- Provide opt-out for activities people find uncomfortable
- Focus on genuine connection, not superficial bonding

---

### Psychological Safety & Inclusion

Intensive collaborative events only work when people feel safe to take risks, ask questions, and be themselves.

#### Creating Psychological Safety

1. **Clear norms and expectations**
   - State inclusivity values explicitly
   - Define Code of Conduct
   - Address power imbalances upfront
   - Explain how to raise concerns

2. **Modeling vulnerable leadership**
   - Facilitators share their own challenges
   - Admit mistakes and uncertainty
   - Ask for help
   - Encourage questions and ideas

3. **Responsive facilitation**
   - Notice when someone isn't participating
   - Invite quieter voices to contribute
   - Intervene in exclusionary behavior
   - Address conflict directly and respectfully

4. **Celebration of diverse perspectives**
   - Different ideas are valued
   - Dissent is encouraged, not suppressed
   - Diversity seen as strength
   - Learn from people who think differently

#### Inclusion Specifics

**For neurodivergent participants**:
- Provide agenda in advance
- Allow breaks and quiet spaces
- Use written and verbal communication
- Minimize surprise changes or loud stimuli
- Support different ways of participating

**For participants with different abilities**:
- Physical accessibility (wheelchair ramps, elevators)
- Visual accessibility (large fonts, descriptions of images)
- Hearing accessibility (captions, live transcription)
- Cognitive accessibility (clear language, written support)

**For marginalized groups**:
- Intentional recruitment and outreach
- Mentorship and support
- Counter microaggressions
- Make feedback safe to give
- Create affinity spaces (optional) for reflection

---

### Documentation & Follow-Up

Events that end with great follow-up have lasting impact.

#### During-Event Documentation

- Take photos with permission
- Record talks/sessions (when appropriate)
- Capture key insights and decisions
- Document contact info and connections
- Note what worked and what to improve

#### Post-Event Follow-Up

**Immediate** (within 1 week):
- Share event photos and materials
- Thank participants and mentors
- Celebrate wins and highlights
- Distribute key resources or documentation

**Short-term** (1-2 months):
- Share outcomes and impact
- Facilitate continued connections
- Gather detailed feedback
- Create opportunities for ongoing community

**Long-term**:
- Maintain communication with alumni
- Invite to future events
- Create mentorship and collaboration opportunities
- Use as case studies and stories

---

## VIRTUAL & HYBRID CONSIDERATIONS

As events move across physical and digital formats, design considerations become more complex.

### Virtual Event Best Practices

**Technical infrastructure**:
- Reliable video platform (Zoom, Google Meet, Gather.town for avatar-based spaces)
- Shared collaboration tools (Figma, Miro, Google Docs)
- Project management and communication (Slack, Discord, Asana)
- Shared code repositories (GitHub)
- Time zone tools (World Time Buddy, Calendly timezone support)

**Engagement strategies**:
- Breakout rooms for smaller discussions and team building
- Chat-based participation (polls, Q&A, emoji reactions)
- Scheduled informal "hallway" conversations (structured networking)
- Shared digital whiteboards for visual collaboration
- Regular on-camera check-ins to build connection

**Accessibility**:
- Captions and transcription (automatic or human)
- Audio descriptions of visual content
- Plain language and jargon explanation
- Option to participate audio-only or video-optional
- Recording available afterward

**Challenges to solve**:
- Zoom fatigue (schedule breaks, camera-optional sessions)
- Technical barriers (support for setup, backup plans)
- Isolation (intentional community building)
- Asynchronous needs (some people can't attend live)

### Hybrid Event Design Principles

The hybrid event challenge: co-located participants have inherent advantages (informal conversations, shared artifacts, mentorship access, recognition). Hybrid design must intentionally eliminate these asymmetries.

#### Equal Participation Architecture

1. **Mentorship equity**
   - Mentors split time between in-person and remote
   - Remote teams get scheduled mentorship slots
   - In-person teams don't get informal mentor advantage
   - Mentorship channel monitored for both groups

2. **Judge fairness**
   - All projects judged using same format/criteria
   - Remote projects submitted (video demo)
   - On-site projects also submitted (backup)
   - Judges assess projects, not presentation quality

3. **Recognition consistency**
   - Awards announced to full group (video call)
   - Remote winners celebrated equally
   - Shout-outs and acknowledgment for both groups
   - No "side" announcements that exclude remote

#### Technical Infrastructure for Hybrid

- Central presentation broadcast to remote participants
- Shared documents and collaboration tools (all access)
- Break-out video rooms for remote team meetings
- Avatar-based spaces (Gather, Spatial.chat) for casual hangouts
- Multiple camera angles showing in-person space
- Clear audio so remote participants hear everything
- Backup communication channel if main feed fails

#### Bridging In-Person and Remote

**Intentional connection points**:
- Opening and closing ceremonies with both groups present
- Team introduction activity with both groups
- Mentor pairing (remote + in-person mentors together)
- Shared rituals (check-ins, celebrations, announcements)
- Informal drop-by sessions (open video rooms)

**Participation scaffolding**:
- Daily structured check-ins with all teams
- Clear participation guidelines sent in advance
- Remote participation expected and supported
- Technical support available for both environments
- Dedicated hybrid coordinator managing flows

**Physical design**:
- Main stage/room visible on camera from all angles
- Mentors move between in-person and video calls
- Shared wall displays visible to camera
- Multiple seating areas for different group sizes
- Quiet rooms for focused work (both in-person and video)

---

## SOURCES & FURTHER READING

### Core References

**Hackathon & Event Organization**:
- [Major League Hacking Organizer Guide](https://guide.mlh.io/) — Comprehensive guide covering hackathon timeline, mentorship, judging, logistics
- [Hackathon Organizer's Guide](https://hackathon.guide/) — Community-driven guide with practical tips
- [HackerEarth Guide to Organizing Hackathons](https://www.hackerearth.com/community-hackathons/resources/e-books/guide-to-organize-hackathon/) — Detailed resource covering all aspects

**Unconferences & Open Space Technology**:
- [Open Space World](https://www.openspaceworld.org/) — Official hub for Open Space Technology resources
- [A Brief User's Guide to Open Space Technology](https://openspaceworld.org/wp2/hho/papers/brief-users-guide-open-space-technology/) — Harrison Owen's foundational guide
- [Facilitator School Guide on Open Space Technology](https://www.facilitator.school/blog/open-space-technology) — Modern interpretation with examples
- [Open Space Facilitator Resources](https://openspaceworld.org/wp2/explore/facilitator-resources/) — Templates and facilitation guidance

**Design Sprints**:
- [The Design Sprint — Google Ventures](https://www.gv.com/sprint/) — Official methodology from GV
- [Design Sprint Kit](https://designsprintkit.withgoogle.com/) — Google's resources and templates
- [The Sprint Book](https://www.thesprintbook.com/the-design-sprint) — Original book by Jake Knapp and team
- [Design Sprint Academy](https://www.designsprint.academy/) — Training and workshops
- [Voltage Control Design Sprint Resources](https://voltagecontrol.com/blog/do-shorter-design-sprints-work/) — Deep dives on compressed sprints

**Workshop Facilitation & Design**:
- [SessionLab](https://www.sessionlab.com/) — Platform with 1000+ facilitation methods and templates
- [SessionLab State of Facilitation 2026](https://www.sessionlab.com/state-of-facilitation/) — Annual report on facilitation trends and practices
- [Mural Design Thinking Tools](https://www.mural.co/) — Whiteboarding and collaboration platform
- [FigJam Icebreaker Ideas](https://www.figma.com/resource-library/icebreaker-ideas/) — Structured icebreaker activities

**Accelerators & Cohort Programs**:
- [MVP Builder: Role of Cohorts in Accelerator Programs](https://mvpbuilder.studio/blog/the-role-of-cohorts-in-accelerator-programs/) — Cohort design and peer learning
- [The Design of Startup Accelerators](https://www.sciencedirect.com/science/article/abs/pii/S0048733319300939) — Academic research on accelerator design
- [GitHub Accelerator](https://accelerator.github.com/) — Modern accelerator program example

**AI & Hands-On Learning**:
- [Crisp's Blog: Mob Programming with AI](https://blog.crisp.se/2025/06/02/michaelgothe/mob-programming-with-ai-inside-a-high-performing-teams-journey) — Contemporary approach to ensemble programming with AI
- [LinkedIn Learning: Pair Programming with AI](https://www.linkedin.com/learning/pair-programming-with-ai) — Practical techniques for AI-assisted development
- [Ensemble (Mob) Programming](https://agilepainrelief.com/glossary/ensemble-programming/) — Modern terminology and practices

**Startup Pitching & Demo Days**:
- [Y Combinator: Guide to Demo Day Pitches](https://www.ycombinator.com/blog/guide-to-demo-day-pitches/) — From leading accelerator
- [Pitch Deck Design with Slidebean](https://www.slidebean.com/blog/startup-demo-day-pitch-deck) — Visual design principles

### Event-Specific References

**Unconference & BarCamp**:
- [BarCamp Wikipedia](https://en.wikipedia.org/wiki/BarCamp) — Format and history
- [Liberating Structures: Open Space Technology](https://www.liberatingstructures.com/25-open-space-technology/) — Modern facilitation framework

**Virtual & Hybrid**:
- [Airmeet: Virtual Hackathon Guide](https://www.airmeet.com/hub/blog/virtual-hackathon-guide/) — Virtual event best practices
- [Devpost: Virtual Hackathon Resources](https://info.devpost.com/blog/how-to-organize-virtual-hackathons) — Platform-specific guidance
- [AngelHack Virtual Hackathons](https://angelhack.com/services/virtual-hackathon/) — Professional virtual event provider

**Icebreakers & Team Building**:
- [SessionLab Icebreaker Collection](https://www.sessionlab.com/blog/icebreaker-games/) — 67 icebreaker activities
- [Miro Icebreaker Templates](https://miro.com/templates/icebreaker-games/) — Visual icebreaker activities
- [University of California San Diego: Icebreakers and Energizers](https://sixth.ucsd.edu/_files/_home/student-life/icebreakers-teambuilding-activities-energizers.pdf) — Comprehensive collection

### Books & Deeper Learning

- **The Sprint Book** by Jake Knapp, John Zeratsky, Brad Kowitz — Foundational guide to design sprints
- **Open Space Technology: A User's Guide** by Harrison Owen — The original work on unconferences
- **Facilitator's Guide to Participatory Decision-Making** by Sam Kaner — Deep dive on group facilitation
- **The Practice of Adaptive Leadership** by Ronald Heifetz — Leadership in complex adaptive systems

---

## QUICK REFERENCE: FORMAT COMPARISON MATRIX

| Aspect | Hackathon | Unconference | Design Sprint | Workshop | Accelerator |
|--------|-----------|--------------|--------------|----------|------------|
| **Duration** | 24-72 hrs | 1-3 days | Multi-day, fixed | 2-8 hours | 3-6 months |
| **Planning** | Structured | Self-organized | Highly structured | Structured | Long-term planning |
| **Facilitator Role** | Active, enabling | Light, background | Strong | Instructor | Mentor, coach |
| **Outcome** | Projects/prototypes | Insights, network | Validated prototype | Skills learned | Company/traction |
| **Participant** | Builders, makers | Learners, experts | Problem solvers | Learners | Founders |
| **Cost** | Medium-High | Low-Medium | Medium | Low-Medium | High (investment) |
| **Ideal Group** | 30-500 | 20-300 | Small team | 8-30 | 10-20 |
| **Learning Style** | Peer + self-directed | Peer + dialogue | Customer feedback | Instructor-led | Mentorship + peer |
| **Virtual Friendly** | Yes | Yes | No (needs presence) | Yes | Hybrid recommended |

---

## FINAL NOTES

Intensive collaborative events are powerful catalysts for learning, innovation, and community building. Success depends on:

1. **Clear purpose** — Why are you bringing people together? What will they achieve?

2. **Intentional design** — Structure supports natural emergence. Detailed planning creates freedom.

3. **Strong facilitation** — Leaders who create psychological safety enable people to do their best work.

4. **Diverse community** — Mix of experience levels, backgrounds, and perspectives generates better outcomes.

5. **Inclusive accessibility** — Design for participation across abilities, work styles, and circumstances.

6. **Focused follow-up** — Events that create lasting impact have strong post-event community and connection.

These principles apply across all intensive event formats. Choose the format that best fits your community's needs, and design with intention and care.

