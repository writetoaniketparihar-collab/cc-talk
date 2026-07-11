# Live demo: create the weekly-report skill

When: right after the Skills "Just three simple rules." slide.

## Step 1. Create the skill

Say to Claude Code: "Can you create this skill for me?" and paste:

name: weekly-report
description: Write my weekly status update from rough notes.
  Use when I say "write my weekly report" or "weekly update".

# Steps
1. Ask for my rough notes: what got done, what's stuck, what's coming.
2. Start with a summary of two lines max.
3. Then three sections, in this order: Done this week, Blocked or at risk, Next week.
4. Bullets, not paragraphs. Keep the whole report to one page.
5. End by showing me the finished report to review before I send it.

## Step 2. Use it immediately

Say: Write my weekly report.

Then paste these rough notes when it asks:

shipped the new onboarding email, open rate 38%
checkout bug from last week finally fixed, took 3 days
legal still has not approved the pricing page copy, waiting since monday
maria is on holiday so the demo video slips a week
next week: prep the q3 review, finalize pricing page if legal replies, interview 2 candidates

## Before the talk

- Delete any old copy so the creation is real: rm -rf ~/.claude/skills/weekly-report
- Rehearse once.

## If the live demo fails

Copy the prepared skill in and show that instead:

cp -R ~/cc-talk/demo/weekly-report ~/.claude/skills/

Then continue with Step 2 as normal.
