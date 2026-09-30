---
"mattpocock-skills": minor
---

wayfinder: support **team maps**. When the repo has a team doc (from `setup-team`), every ticket gets an **owner** (assignee plus an `area:<area>` label) at creation, and the claim moves to a `wayfinder:in-progress` label, so ownership and "someone is on it now" are separate. Each dev's session takes their own tickets first and asks before claiming someone else's; team drift on load triggers proposed reassignments, applied only on confirmation. Without a team doc, behaviour is unchanged. Also documents invoking `/wayfinder` with a ticket rather than the map.
