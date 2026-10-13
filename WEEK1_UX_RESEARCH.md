# FitTrack — Week 1 UX Research & Wireframes

**Deliverables:** two proto-personas, empathy maps, user journey, information architecture, five-screen concept, moodboard direction, usability test plan, and clickable HTML prototype.

> **Research integrity:** The personas and insights below are illustrative proto-personas/hypotheses, not claims from interviews already conducted.

## 1. Problem statement
People may struggle to maintain exercise routines when fitness apps feel complicated, workouts seem too long, or progress is difficult to understand. FitTrack aims to make the next action clear and progress encouraging.

### Research goals
- Understand motivations and barriers to consistent activity.
- Identify what users need to see at a glance.
- Map the journey from opening the app to reviewing a workout.
- Check whether a simple flow supports beginners and regular exercisers.

## 2. Proto-personas

### Aisha Khan — busy beginner
- **Context:** 24, early-career professional with a variable schedule.
- **Goals:** build a manageable three-day routine and improve energy.
- **Needs:** short workouts, clear instructions, flexible reminders, visible progress.
- **Frustrations:** complex dashboards, jargon, guilt-inducing streaks.
- **Behaviours:** uses her phone between tasks; prefers 10–20 minute sessions.
- **Illustrative quote:** “Help me start small and keep going without making me feel bad.”
- **Design implications:** quick-start options, plain language, and an easy restart after missed days.

### Rahul Mehta — goal-driven regular
- **Context:** 29, full-time worker who exercises 4–5 days a week.
- **Goals:** monitor weekly activity, improve performance, stay accountable.
- **Needs:** fast logging, useful trends, editable goals, workout history.
- **Frustrations:** too many taps, unclear charts, unexplained metric changes.
- **Illustrative quote:** “Show me what changed this week and let me log a session quickly.”
- **Design implications:** concise logging, contextual trends, transparent metric definitions.

## 3. Empathy maps

### Aisha
- **Says:** “I only have 15 minutes.” “I don’t know which workout to choose.”
- **Thinks:** “Can I do this safely?” “Can I stay consistent?”
- **Does:** searches for beginner workouts and postpones exercise when plans feel too large.
- **Feels:** motivated initially, uncertain about technique, discouraged after missed days.
- **Pain points:** choice overload, jargon, rigid plans.
- **Opportunities:** simple recommendations, time estimates, supportive feedback.

### Rahul
- **Says:** “Did I improve this week?” “Logging should take seconds.”
- **Thinks:** “Are these numbers accurate?” “What should I focus on next?”
- **Does:** tracks sessions, checks weekly totals, adjusts goals.
- **Feels:** motivated by progress, frustrated by unclear metrics.
- **Pain points:** slow logging, shallow history, unexplained numbers.
- **Opportunities:** quick activity entry, weekly trends, goal controls.

## 4. User journey — completing a workout

| Stage | User action | Thought / feeling | Friction | Design response |
|---|---|---|---|---|
| Open | Opens app | “What should I do?” | Busy dashboard | Clear summary and primary action |
| Choose | Selects workout | “Will it fit my day?” | Duration unclear | Show time, level and equipment |
| Prepare | Reviews details | “Can I follow this?” | Unclear instructions | Simple steps and accessible labels |
| Track | Starts activity | “Is it recording?” | Too many controls | Prominent start, pause and finish |
| Review | Sees summary | “Did I progress?” | Numbers without context | Plain-language summary |
| Return | Plans next session | “I can do this again.” | Guilt after missed days | Flexible, encouraging next step |

## 5. Information architecture
- **Home:** daily activity, weekly progress, start workout.
- **Workout:** activity details, duration, difficulty, tracking controls.
- **Progress:** weekly activity, completed sessions, goal progress.
- **Settings:** personal goals, reminder preferences, privacy controls.

## 6. Five low-fidelity screens
1. **Welcome/setup:** value statement, goal selection, continue.
2. **Home dashboard:** greeting, activity summary, weekly progress, start CTA.
3. **Workout selection:** activity list with duration and difficulty.
4. **Active workout:** elapsed time, activity, pause and finish actions.
5. **Workout summary:** completion state, duration, progress, next-step CTA.

See `fittrack-prototype.html` for a clickable HTML concept that demonstrates these five screen structures. It is a learning prototype, not a production tracker.

## 7. Moodboard and visual direction
- **Personality:** calm, encouraging, clear and energetic without pressure.
- **Palette:** navy #14213D; mint #7BDCB5; warm off-white #F7F7F2; slate #657080; coral #FF8066.
- **Typography:** readable sans-serif, clear hierarchy, comfortable line spacing.
- **UI principles:** large touch targets, strong contrast, progress never shown by colour alone, optional reminders, no shame-based language.
- **Imagery:** inclusive everyday movement rather than unrealistic body ideals.

## 8. Usability test plan
**Participants:** 4–5 people with mixed fitness experience. **Method:** 15–20 minute moderated prototype test with consent.

**Tasks**
1. Find a beginner workout lasting 15 minutes or less.
2. Start a workout and explain how to pause it.
3. Finish and explain the summary.
4. Find weekly progress and locate goal/reminder settings.

**Measures:** task success, time on task, mis-taps, confidence rating (1–5), confusing labels and participant comments.

**Questions:** What did you expect this control to do? What information was missing? Was anything unclear or discouraging? What would make you return?

Do not report usability findings until sessions have actually been conducted. Record observations and iterate from evidence.

## 9. Accessibility checklist
- Readable text and strong contrast.
- Never rely on colour alone.
- Descriptive button labels and generous touch areas.
- Screen-reader names and logical focus order.
- Respect reduced-motion preferences.
- Reminders opt-in and easy to change.
- Support restarting after missed days.

## 10. Next steps
1. Validate proto-personas through real interviews.
2. Create/refine the five frames in Figma.
3. Run usability tasks and document observations.
4. Iterate wireframes from the results.
5. Add the Figma share URL if a native Figma deliverable is required.

**Submission note:** This repository includes the research package and clickable HTML prototype. The assignment screenshot mentions Figma, so create/import the frames in Figma if the instructor requires a native Figma file.
