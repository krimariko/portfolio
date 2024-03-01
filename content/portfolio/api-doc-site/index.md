+++
title = 'Starwipe API Documentation Site'
date = 2024-02-06T14:29:06-08:00
showTableofContents = true
draft = false
+++

## Project overview

This was my final group project for the UW Technical Writing certificate program.

We built an API documentation site for a made-up photo hosting service named Starwipe. We started by desiging a simple REST API following the OpenAPI spec. We built the whole thing with Stoplight.

## User Research

Primary users: software developers implementing API

Secondary:

Tertiary:

After sketching out a high level project plan, we started by talking to software developers about what they look for in good API documentation. Some pretty common themes surfaced regarding best practices and pain points. We gathered a working list of documentation dos and don'ts and from there built a persona of our target user and mapped out their documentation user journey.

We used [Figma](https://www.figma.com/) to create all research artifacts.

### Talking to our users: what developers had to say about API documentation

We gathered responses from a total of 9 developers using a combination of live interviews and Google form polling.

#### What we asked

1. Have you worked with APIs before? (all yes)
2. When & why would you seek out API documentation?
3. What is the first thing you look for in API documentation?
4. What is something you frequently find you need in API documentation, but often discover is missing?
5. What distinguishes good API documentation from poor documentation?
6. Can you think of any examples of good API docs? What makes this example stand out?
7. Are there any immediate telltale signs of bad API documentation? For example, if you were to take a quick glance at an API doc site, is there anything that would make you jump ship immediately?

#### What we learned
Happily our interviewees pretty much agreed about what sets apart good docs from poor ones.

**Here are the main takeaways:**
- Authentication instructions need to be front and center. This is critical information that's often hidden or just not included. If we can't figure out how to authenticate, we can't use the API.
- They want website/documentation where they can collapse down different categories and not do a ton of scrolling (unsure if this is possible for our final deliverable with our limited experience, but we can certainly make something skimmable and easy-to-navigate at the least)
- Beneficial to have a getting started/tutorial/first steps section.
- Documentation that hasn't been updated recently or is out-of-date is a big red flag. Old information means the docs aren't reliable.
- Examples are key. Lots of examples in a variety of languages means we can get up and running quickly.
- Lack of troubleshooting information is frustrating. Developers don't want to spend time debugging the API through trial and error. Docs should provide guidance.
- Comprehensive and clearly organized reference section containing all available endpoints.
- Different types of docs for different parts of the user journey. Conceptual articles for users in the evaluation/getting started phase. Reference for users in implementation phase.

### User persona

[link]

### Empathy map

[link]

### User journey

[link]