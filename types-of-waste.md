# Types of waste

- Building the wrong thing
  - Features that don't add value and/or complicate the UX
  - Leads to rework and/or ongoing maintenance and operations work
  - Sometimes caused by not defining problem and solution correctly
- Not building and shipping quickly enough
  - Long lead times are bad - no value realized until feature is shipped
  - Can be caused by external team dependencies, which in turn can be an indicator of poor organizational design
  - Can be caused by poor planning
  - Leads to need to frequently rework unshipped code (e.g. rebasing and accommodating changes in mainline)
  - Demoralizing
  - Can be caused by interruptions to developer flow
    - Do not waste colleagues' time with pointless meetings or exercises. Be mindful of the appropriate communication method depending on what you are trying to achieve (e.g. async/sync, there is a full spectrum of options here)
    - Can be caused by waiting on slow builds, tests, CR (Code Review) etc.
      - Make sure all automated processes that block developers are _fast_
      - Ensure a culture of unblocking colleagues quickly (e.g. when CR is required)
- Too much WIP (Work in Progress)
  - Context switching breaks developer flow
  - Demoralizing
  - Too much WIP slows down lead times (see [Little's Law](littles-law.md)) and all the associated issues
- Over-complicating the solution (either UX or engineering complexity).
  - Solutions should minimize accidental complexity whilst paying heed to essential complexity
- Defects
  - Bugs harm the product and errode customer confidence
  - Caused by mistakes in problem definition and solution design
  - Caused by insufficient test coverage
  - Requires rework

---

Inspired by [Toyota's seven forms of waste](<https://en.wikipedia.org/wiki/Muda_(Japanese_term)>):

1. Transportation
2. Inventory
3. Motion
4. Waiting
5. Overproduction
6. Over-processing
7. Defects
