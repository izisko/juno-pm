# Prototype · Juno

> Module 2 · Prototype. The working build that tests your idea, made with your build tool of choice.

## Prototype link

HTML file :)

_____

## What it demonstrates

On Monday, a PM reviews recent NPS feedback grouped by recurring problem. For each group, Juno links to Webex conversations and Jira records, shows whether the issue is tracked, and suggests a source-linked ticket draft and reproduction steps when there’s no clear match. Unclear or conflicting comments stay flagged for the PM to review.

_____

## Debrief -> already implemented

- **What worked:** Moving “Needs your review” to the top made the first step clearer. The category row shows what’s present and what’s empty, while expandable group cards keep the evidence available without putting it all upfront.
- **What broke / felt like a toy:** The action and date controls only save in this browser; they don’t reply, delegate, escalate, or change Jira. The categories are illustrative, and three groups don’t show how the grid would scale.
- **What I'd change next pass:** Test with a PM whether they can quickly choose what to do and by when. Validate the category rubric and action labels with them, then try the layout with more groups and real source evidence.
