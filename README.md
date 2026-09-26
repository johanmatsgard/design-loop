# Design loop

An autonomous design process I run in Claude Code on the customer portal for Elvy's installation phase, the period between a customer signing and their heat pump being up and running. The code and screens are private, so this is a write-up of the method.

## Why

The portal has one main job: get customers to do the things that block their installation, like booking a site visit, before a deadline. I also wanted it to be genuinely good to use, not just functional. The loop lets me explore a lot of directions quickly while I decide where it goes.

## How it works

The loop is split into five parts, each looking at one side of the experience:

| Loop | Looks at |
|---|---|
| CONVERT | Getting the blocking action done |
| CUSTODY | The wait between steps, and keeping the customer confident during it |
| DAY | Site visit, delivery and installation day |
| VOICE | Copy and numbers |
| CRAFT | The details that make it feel distinct |

One run goes through all five and then stops with a review card: what changed, why, and what it wants to try next. I read it, steer, and start the next run.

After two cycles the current version is frozen and the loop forks a new one. A new version has to be a different design idea built on the same data layer, not a restyle of the last one. That keeps the loop from polishing one direction forever.

## Rules it works under

- A shared contract in `docs/loop/CORE.md` that every loop reads first
- Loop state kept in `.design-loop/` so a run can pick up where the last one stopped
- Typefaces locked to the brand; the rest of the design system can be pushed
- Judged on a phone first, and desktop must still hold up
- Mock data only

## Where it ended up

The versions from the loop went to our tech team as the basis for the first web version of the portal, which they're building now. The same approach is being used for the app version.
