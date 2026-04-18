# User Constraints Card & Product Planning

## What Is a User Constraints Card?

A User Constraints Card forces you to get specific about who you are building for. Vague users lead to vague products. Specific users lead to specific, useful features.

Here is the key insight: constraints are more useful than preferences. Knowing that your user "likes fun designs" tells you almost nothing. Knowing that your user "plans parties on their phone during lunch break and has 10 minutes before their friends arrive" tells you everything.

Fill out this card for your Event & Party Planner:

| Question | Your Answer |
|----------|-------------|
| What age or type of person is your user? | (e.g., "a grade 6 student," "a parent of young kids," "a teacher") | A grade 8 student, 13 years old.
| When would they use this tool? | (e.g., "2-3 weeks before a birthday party") | A week before a trip or a busy week.
| How long would a typical session last? | (e.g., "10-15 minutes to set up an event") | 5-10 minutes to set up an event.
| What would make them stop using it? | (e.g., "too many steps," "confusing layout," "cannot find their guest list") | Cannot find certain things like guest list or specific events.
| What do they care about most? | (e.g., "getting everything organized in one place") | Everything accessible and organized for efficient planning.
| What do they dislike about planning events? | (e.g., "forgetting who is coming," "not knowing what activities to plan") | Not knowing what activities to plan.

Your answers here drive every decision you make today. If you cannot answer these questions, your rebuild will be unfocused.

## Top 3 User Needs

You cannot build everything. Professional product teams pick the 3 most important things and do them well. Everything else waits.

From your User Constraints Card, pick only 3 needs that matter most to your target user:

Example needs for an Event & Party Planner:

- Easy, fast event creation (name, date, theme in under 2 minutes)
- Visual theme preview so the user can see what their party will feel like
- Simple guest management (add names, track who is coming)
- Shareable event link so guests can see details
- Activity schedule builder with time slots
- Print-friendly event summary

Pick your 3. Write them down. Everything else is secondary.

1. **Need #1:**
Guest List: To keep everyone going organized.

2. **Need #2:**
Folders: To organize and store lots of events at once.

3. **Need #3:**
Budget: To organize budget for parties and trips.

## Product Positioning Sentence

A Product Positioning Sentence describes what you are building in one line. It forces clarity.

Template:  "A ______ tool for ______ that gives them ______"
Examples:

- "A party planning tool for grade 6 students that gives them a simple way to organize themes, guests, and activities in one place"
- "A quick event builder for parents that gives them a shareable party plan they can send to guests"
- "A classroom event planner for teachers that gives them a printable schedule with activities and a guest checklist"

Write yours. If you cannot finish the sentence, you do not know what you are building yet.

## MVP Scoping

MVP stands for Minimum Viable Product. It is the smallest version of your product that delivers real value to your target user. Not the smallest version you can build -- the smallest version that matters to someone.

The core interaction loop for an Event & Party Planner is:

Create event --> Add details --> Manage guests --> Plan activities --> Preview/share

Your MVP must complete this loop. Everything that supports the loop is must-have. Everything else is nice-to-have.

**Tip**  
A feature is Must-Have only if removing it breaks the core loop. Can someone create an event, add guests, and plan activities without it? If yes, it is Nice-to-Have.

## Challenge 1: User Constraints Card & Top 3 Needs

**Note**  
Reference: Setup Guide

**Steps:**

1. Open your v1-diagnosis.md from Lesson 1 and review your target user notes
2. Copy the User Constraints Card template into a new document called user-constraints.md
3. Fill in every field with specific, honest answers -- no "everyone" or "anyone"
4. From your User Constraints Card, identify your Top 3 User Needs and write them as a numbered list
5. For each need, write one sentence explaining WHY it matters to this specific user
6. Read your User Constraints Card out loud. Does it describe a real person you can picture? If it sounds like it could describe "anyone," rewrite it.

**Tip**  
The best constraints cards read like a short story about a real person. "Maya is 12, planning her birthday party for 15 friends. She is using her mom's laptop after school. She has 20 minutes before dinner. She needs to figure out the guest list, pick 3 activities, and text the details to her friends." That level of specificity makes every product decision easier.

## Challenge 2: Product Positioning & K/C/D Audit

**Note**  
Reference: Git & GitHub Guide

**Steps:**

1. Write your Product Positioning Sentence using the template: "A party/event planning tool for kids and parents that gives them a easy way to organize guest lists, activites, and budget all in on place."

2. Audit your K/C/D list from Lesson 1. Go through every element in the AI draft and justify each decision through your user lens:

| Element | K/C/D | Reason (Connected to User Need) |
|---------|-------|-------------------------------|
| Event name field | Keep | Directly serves Need #1 -- users need to name their event |
| Theme dropdown with 8 options | Change | Too many choices -- reduce to 4 so a 12-year-old can decide quickly |
| Generic color scheme | Change | Does not match any theme -- should visually reflect the selected party type |
| Location map embed | Delete | My user just needs a text field for location, not a map |

3. Check every "Keep" and "Change" item connects to at least one of your top 3 needs. If it does not, move it to Delete or demote it to Nice-to-Have.

4. Separate features into Must-Have and Nice-to-Have:

- **Must-have:** Features required for the core interaction loop
- guest lists
- folder
- activity adder
- **Nice-to-have:** Features that enhance but are not essential
- log in
- budget
- prettier website
- **Cut:** Features you are explicitly NOT building
- video games
**Tip**  
Your MVP scope should fit on an index card. If it takes a full page to describe, you are trying to build too much.