class: center
name: title
count: false

# Team Goals

## Iterating towards a roadmap

.p60[![Ferris](./images/ferris.svg)]

.me[.grey[*by* **Nicholas Matsakis**]]
.left[.citation[View slides at `https://nikomatsakis.github.io/team-goals-2024/`]]

---

# Remember roadmaps?

Me too.

---

# Where I think we want to be

* Taking and tracking goals
    * "Do X by Y"
* Taking a goal requires
    * Owner commitment
        * adequare resources to do the job
    * Team commitment
        * assigning a liaison
        * doing reviews

---

# Status quo (lang team)

* Experiment (optional)
    * requires a lang team "second"
* Author RFC
    * requires FCP
* Implement, get feedback, iterate
    * requires compiler team review
* Stabilize
    * requires FCP

---

# Failure modes

## LIMBO

* no decision is reached, team may not even respond
* owner is left with uncertainty:
    * is this idea doomed?
    * how should they move the ball forward?

---

# Failure modes

## TEAM OVERCOMMITED

* trying to do too many things at once
* not enough bandwidth to support ongoing projects
* people are unsure what things to prioritize

---

# Failure modes

## TEAM UNDERCOMMITTED

* no *mandate*
* unclear to owner how hard to push
* not sure what things to prioritize

---

# Failure modes

## NO COMPROMISES

* roadblock in the design stalls progress
* easy to lose track of time and just feel stuck

---

# Failure modes

## OPAQUE

* what is "Rust" working on?
* who is working on it?
* how much progress have they made?

I have no idea.

---

# Failure modes

## GETTING PAID

Companies looking to drive work in Rust today face great uncertainty.

---

# Failure modes are demoralizing

---

# Failure modes make it hard to justify funding

---

# Proposal: Goal RFC

* Motivation and background

--
* Axioms

--
* Immediate goal and milestones

--
* Support required

--
* Vision and long-term goals (optional)

---

# Key idea

## OWNERS

Goal RFC put forward by *owners*.

Owners drive the design.

RFC describes resources they will apply (e.g., developers).

Owners make proposals, teams approve and give feedback.

Insufficient experience with owners' design taste is a valid reason not to accept.

---

# Key idea

## SHORT-TERM GOAL

Goal RFC must have a duration of <= 1 year.

Should include milestones so we can assess progress.

---

# Key idea

## TRACKING PROGRESS

All goals have milestones with dates. 

We should publish regular blog posts summarizing progress towards accepted goals.

---

# Key idea

## SUPPORT REQUIRED

RFC should clarify what resource needs from the Rust project.

e.g., design meeting every other month to review progress, or dedicated reviewer(s). Teams should develop some "templates" for this.

---

# How it fits in

* Experiment (optional)
* Goal RFC (optional)
* Author RFC
* Implement, get feedback, iterate
* Stabilize

Note that goal RFCs should not be **required** and should be reserved for things that the team is **committed to**.

---

# Envisioned pattern 1

## Team goals

Example: Types team goal to land coherence solver

---

# Envisioned pattern 2

## Addressing a new domain

Example: Async

Example: Rust-for-Linux

---

# Envisioned pattern 3

## Rust leader queues up ideas

* Write up a Goal RFC for ideas you have
* Find people to "own" it

---

# What to do when we fail

The reality of scheduling:

* Ship everything you planned *or*
* Ship on time

Pick one.

---

# What to do when we fail

## CUT SCOPE

Example: Original async WG goal for 2023 was to ship AFIT with RTN.

We cut scope along the way.

---

# What to do when we fail

## FILE A NEW GOAL

---

# How this helps

## LIMBO and OVERCOMMIT

* Team should be committing to regular review for goals on a given cadence, which in turn implies a limit to how many goals a team can take.

---

# How this helps

## UNDERCOMMIT

* Team has established that the goal matters and that they would like to see it achieved.
* It should be prioritized above other things.

---

# How this helps

## NO COMPROMISES

Having a date to work against and a goal to ship *something*, even if you must *cut scope*, can prevent indefinite stalls.

---

# How this helps

## OPAQUE

Regular blog posts make it easier to track what goals we are working on.

---

# How this helps

## GETTING PAID

Contractor or employee can build out a *goal RFC* and negotiate with team, which becomes a joint commitment, and can give contractor confidence they can deliver.

---

# Does not solve everyting

* How does team decide which goals to take?

--
* How does team know if goal is attacking domain in the right way? (User research will be required)

--
* How do we gather better feedback before stabilization?

---

# Questions for discussion

* Would this be a good fit for your team?
* Should we have a "goal setting season" (e.g., end of year)?

