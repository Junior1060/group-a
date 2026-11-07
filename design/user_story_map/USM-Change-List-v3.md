# User Story Map: Change List for Version 3

**Why.** Version 2 (October 23) still maps the standalone research website. Since then our work has moved to the main APSS website, and the November 4 check-in added an emergency exit button and a Student Placements section. This list turns the map into a map of the main site. Make the changes below in StoriesOnBoard, then export to PDF as User-Story-Map-v3.pdf in this folder. Keep the v1 and v2 PDFs as before snapshots.

**Status, November 7.** We made these changes by importing [USM-v3-import.xlsx](USM-v3-import.xlsx) as a new map instead of typing them, so section 1 was not needed and the v2 map is unchanged. The StoriesOnBoard PDF export cut story text off after four lines, so [User-Story-Map-v3.pdf](User-Story-Map-v3.pdf) is laid out separately from the map's Excel export.

**Legend.** Activity (blue), Task (yellow), Story (white). Each story line gives the release, what to do with the card, the card text, and where the story came from in brackets. "Site review" means [Main-Site-Redesign-Notes.md](../sitemaps/Main-Site-Redesign-Notes.md).

**Size.** 6 new activities, 25 new tasks and 38 new stories to type. The other cards already exist in v2. We kept every story to 100 characters or fewer because the v2 export cut off a 103-character card.

**Where Research lives.** Our documents disagree. The usability summary and the site review, both from October 21, say Research links out to a separate site. The October 21 check-in notes and the lecture principles document, both added November 6, say it merges into the main site. This list assumes merged, because those are the newest notes and we are building one WordPress site. If the team decides on two sites, only one thing changes: keep the v2 "link to the main APSS site" card. Every other story works either way.

**Releases.** MVP 1 is what we want live by December 2. Our notes show no feedback from Erin on the split yet, so this is our proposal. We put in MVP 1 anything we were asked for by name and anything that helps someone reach a service, because Erin told us most visitors are community members looking for services. Most Learn and About pages can follow in MVP 2.

## 1. Clean up the v2 map

Do these in order, so no card gets deleted with its activity.

- [ ] Rename **Discover Research** to **Arrive at Home**.
- [ ] Rename **Browse Projects** to **Explore Research**.
- [ ] Add the new activities: **Leave Quickly**, **Get Help** and **Learn** after Arrive at Home, then **Get Involved**, **About APSS** and **Use Any Page** after Explore Research.
- [ ] Move these tasks, with their cards, into Explore Research: Find research (from Arrive at Home), Overview, Articles, Posters, Blog.
- [ ] Rename Find research to **Find Research**, Overview to **Project Details**, and Blog to **Research News**.
- [ ] Move the task reportneedles, with its card, into Get Help and rename it **Report a Needle**.
- [ ] Delete the tasks Status and Updates. Neither has any stories, and project status is now part of Project Details.
- [ ] Delete the task APSS and its card, "As a community member, I want a link to the main APSS site, so I can find services".
- [ ] Delete the activities Understand Project, Access Materials, Follow Updates and Connect Sites, which should now be empty.

## 2. The map, left to right

### Arrive at Home

**What is this site?**

- [ ] MVP 1, keep: As a first-time visitor, I want to see what this site is for, so I know if it is for me (v2)
- [ ] MVP 1, new: As a community member, I want real photos of APSS people, so the site feels like a community (empathy map 5, affinity diagram)

**Find My Way** (new task)

- [ ] MVP 1, new: As a community member, I want one-click tiles for key services, so I can find help fast (affinity diagram, ideas list)
- [ ] MVP 1, new: As a visitor, I want the home page to show every main section, so I see all that APSS does (Oct 7 check-in)

**See What's New** (new task)

- [ ] MVP 1, new: As a community member, I want the latest news on the home page, so I see what APSS is doing (affinity diagram)
- [ ] MVP 2, new: As a funder, I want impact numbers on the home page, so I can see what APSS has achieved (affinity diagram)

### Leave Quickly

**Emergency Exit** (new task)

- [ ] MVP 1, new: As someone looking up testing, I want an exit button on every page, so I can leave fast (Nov 4 check-in)
- [ ] MVP 1, new: As someone looking up testing, I want exit to open a neutral page, so my screen stays private (Nov 4 check-in)

Build note: the button has to be easy to see and reach on every page, including on a phone. Use `location.replace` so that Back does not return to the page the person was on. This cannot remove earlier pages from their browser history, so we need to raise that with Erin (section 4).

### Get Help

**Testing** (new task)

- [ ] MVP 1, new: As a community member, I want testing days shown up front, so I know when I can go in (site review)

**Needle Exchange** (new task)

- [ ] MVP 1, new: As a community member, I want needle exchange info one click away, so I can get supplies (affinity diagram, sitemap)

**Report a Needle** (moved from Connect Sites)

- [ ] MVP 1, move: As a community member, I want a link to reportneedles.ca, so I can report a needle quickly (v2)

**Naloxone** (new task)

- [ ] MVP 1, new: As a community member, I want naloxone listed under Get Help, so I can find kits and training (site review)

**Care & Support** (new task)

- [ ] MVP 1, new: As a client, I want HIV and opioid care info together, so I can find the care I need (sitemap)
- [ ] MVP 1, new: As a community member, I want to see APSS support groups, so I can find one that fits me (sitemap)

**Visit Us** (new task)

- [ ] MVP 1, new: As a community member, I want hours and a map link, so I know when and where to go (site review)

### Learn

**Find a Topic** (new task)

- [ ] MVP 1, new: As a community member, I want a short list of topics, so the menu does not overwhelm me (site review, ideas list)

**Health Basics** (new task)

- [ ] MVP 1, new: As a community member, I want plain-language HIV and hep C basics, so I can understand them (insights chart, sitemap)
- [ ] MVP 2, new: As a community member, I want fact sheets on one page, so I do not have to hunt for them (site review)

**Harm Reduction** (new task)

- [ ] MVP 2, new: As a community member, I want harm reduction and overdose info, so I can stay safer (sitemap)

**Cree Resources** (new task)

- [ ] MVP 2, new: As a Cree speaker, I want Cree resources easy to find, so I can read in my own language (sitemap)

**FAQs** (new task)

- [ ] MVP 2, new: As a first-time visitor, I want FAQs in the footer, so I can get quick answers from any page (affinity diagram)

### Explore Research

**Find Research** (moved from Discover Research)

- [ ] MVP 1, new: As a funder, I want Research in the main menu, so I can find APSS research in one click (Oct 21 check-in, site review)

**Current Projects** (already here)

- [ ] MVP 1, keep: As a funder, I want to see current projects, so I know what APSS is working on (v2)
- [ ] MVP 2, keep: As a researcher, I want to filter projects by category, so I find relevant work faster (v2)

**Completed Projects** (already here)

- [ ] MVP 1, keep: As a funder, I want to see completed projects, so I can judge APSS's impact (v2)

**Project Details** (renamed from Overview)

- [ ] MVP 1, reword: As a researcher, I want a project's partners and status together, so I can decide to cite it (v2, this is the card that was cut off)
- [ ] MVP 2, move: As a researcher, I want to see related projects, so I can explore connected work (v2)

**Articles** (moved)

- [ ] MVP 1, move: As a student, I want to open journal articles, so I can use APSS research in my work (v2)
- [ ] MVP 1, new: As a student, I want a publisher link when APSS cannot host a PDF, so I can still read it (README publication rights constraint)
- [ ] MVP 2, move: As a student, I want related articles and posters on each project, so I do not have to search (v2)
- [ ] MVP 2, new: As a community partner, I want community reports with the research, so I can share results (insights chart)

**Posters** (moved)

- [ ] MVP 1, move: As a community partner, I want to view research posters, so I can share them at events (v2)
- [ ] MVP 2, new: As a community partner, I want to download a poster PDF, so I can print it for events (Oct 7 check-in, some posters are paper only and need scanning)

**Research News** (renamed from Blog)

- [ ] MVP 1, move: As a community partner, I want to read the latest research news, so I stay informed (v2)

### Get Involved

**Volunteer** (new task)

- [ ] MVP 1, new: As a community member, I want a clear way to volunteer, so I can start helping (affinity diagram)

**Donate** (new task)

- [ ] MVP 1, new: As a supporter, I want a Donate button on every page, so I can give when I am ready (sitemap)

**Student Placements** (new task)

- [ ] MVP 1, new: As a student, I want a placements page, so I can find opportunities and how to apply (Nov 4 check-in)

**Events & News** (new task)

- [ ] MVP 1, new: As a community member, I want events and news together, so I can see what is coming up (site review, affinity diagram)
- [ ] MVP 1, new: As APSS staff, I want to post news and events myself, so the site stays current (Oct 21 check-in)

**Careers** (new task)

- [ ] MVP 2, new: As a job seeker, I want openings listed under Get Involved, so I can apply to work at APSS (sitemap)

### About APSS

**Who We Are** (new task)

- [ ] MVP 1, new: As a funder, I want a short overview of APSS, so I can decide whether to support it (Oct 7 check-in)

**People & Partners** (new task)

- [ ] MVP 2, new: As a community partner, I want to see APSS's team, board and history, so I know who runs it (sitemap)
- [ ] MVP 2, new: As a funder, I want to see APSS's supporters and partners, so I know who backs its work (sitemap)

**Reports & Plans** (new task)

- [ ] MVP 2, new: As a funder, I want annual reports one click from About, so I can check APSS's results (site review)

### Use Any Page

**Header** (new task)

- [ ] MVP 1, new: As a community member, I want Get Help first in a short menu, so I can find services fast (Oct 7 check-in, ideas list)
- [ ] MVP 1, new: As a community member, I want the phone and today's hours on every page, so I can reach APSS (sitemap)

**Footer** (new task)

- [ ] MVP 1, new: As a visitor, I want the same footer on every page, so I can always find key links (affinity diagram, sitemap)

**Phone** (new task)

- [ ] MVP 1, new: As a community member, I want the site to work on my phone, so I can use it anywhere (status report)

**Language** (new task)

- [ ] MVP 2, new: As a French, Spanish or Portuguese speaker, I want to switch language, so I can read the site (Oct 7 check-in)

## 3. Map annotations, not stories

- [ ] WCAG 2.1 AA (README).
- [ ] White page, neutral colours, coloured footer (Oct 7). Darker, richer tones, no peach (Oct 21).
- [ ] Real APSS photos, no AI images (empathy maps, affinity diagram).

## 4. Confirm with Erin

- [ ] Which neutral page should the exit button open? The November 4 notes give a local weather site or the Google homepage as examples.
- [ ] The exit button cannot clear browser history. Does APSS want a short note on the site explaining this?
- [ ] Is our MVP 1 and MVP 2 split right, and does the language switcher need to move into MVP 1?
- [ ] Are the COVID-19 and Mpox fact sheets still needed?
- [ ] Who updates WordPress after December 2? This has been open since October 7, and the APSS staff story depends on it.
- [ ] Which articles and posters are paper only, and who scans them?

## 5. Export and record

- [ ] StoriesOnBoard: Export, PDF, whole map, with the release lines visible.
- [ ] Read every card in the PDF. If one is cut off, shorten it and export again.
- [ ] Save as design/user_story_map/User-Story-Map-v3.pdf. Do not overwrite v1 or v2.
- [ ] Add one line to the November 4 check-in notes saying what changed on the map.

## How this connects to class

These use the concept names from our [design rationale](../../docs/design_principles/Design-Principles.pdf).

- **Constraints.** A short menu and a short list of Learn topics limit the choices on screen, so people are less likely to get lost. This answers the note in our ideas list that the current menus can seem frightening and distracting.
- **Affordances and signifiers.** The exit button has to look like a button and say what it does, because nobody should have to work it out when they need to leave. Report a Needle keeps its ↗ marker because it leaves our site.
- **Feedback and consistency.** The exit button, header and footer stay the same on every page, so people can find them without searching.

The newsletter, "other links" and "other resources" items from the v2 change list are left out on purpose, because none of them are on the redesigned sitemap.
