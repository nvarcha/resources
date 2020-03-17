---
path: "/projects/software/scrum-of-scrums"
title: "Scrum of Scrums"
---

# The above values are used for the website, please make sure to fill them out.

# PLEASE COPY THE DOCUMENT AND START YOUR PROPOSAL ON YOUR COPY 
| | |
|-|-|
| Proposal Stage |      |
| Tags           |      |
| Created Date   |      |
| Lead           |      |
| Slack Channel  |      |

## 📃 Idea in brief: Question to be resolved and why
How can we organize thousands of developers and other specialists effectively to get the most work done as fast as possible?

### 💥 Problem
Once we have projects approved, we have no easy way to manage them and, more specifically, to produce (develop, test, etc.) them.
Building a team is hard. Volunteers may not have long hours to work. A high rotation is expected and that could jeopardize the completion or velocity of a project that could very well save lives.

### 👨‍🔬Hypothesis
We can develop a website where SCRUM teams can be registered or assembled automatically by the system based on roles (i.e.: 1 Scrum Master, 1 front-end dev, 1 back-end dev, 1 QA, 1 UI/UX). Users would register based on roles, locations and language.
Each project's leads would post User Stories (or "working units"), and scrum masters of teams can "assign" such User Stories to the team, develop, test and deliver through pull requests.

### 🤔 Assumptions
There is an ongoing project for community management which could handle projects as a high level approval and filtering. Approved projects can then be fed to this system and get a fast development cycle.

## 💻Implementation Suggestion

### V1
- Create CRUD for volunteers to sign up
- Create CRUD for projects to be added (with admin access)
- Create a Team Definition criteria for the system to assemble teams
- Notify team members about their team and assigned project
- Create CRUD for projects' User Stories
- Allow teams' Scrum Master to assign a User Story to the team


### What it is
It is a unified, global tool to spontaneously assemble teams, define User Stories, assign them, develop them, and repeat.

### What it is not
- A community project organization (there's another project for that)
- Slack/Zoom replacement (teams should still coordinate through Slack/Zoom)

### Design

### Data/Experiments

V2
- Implement Slack integration (to create channels and remove them once Pull Request is approved)
- Allow team members to join "as team" in case they know each other, which could improve outcome
- Integrate with Github for easier assignment, tracing and peer review


## 💪 Impact of Potential Solution
- Empowers Helpful Engineering's efforts
- Organizes developers
- Speeds up projects development

## 🙌 Criteria for Success
- 200 or more Scrum teams organized and working at the same time

## 😅 Known Issues
- Need servers (AWS?)

## ✅ "I've read this" section
Add in the table below the people you definitely want their eyes on this proposal. Sometimes there are no comments to be made but it's good to know people have read the proposal

| Name | Status |
|-|-|
|  |  Read/Not Read    |
