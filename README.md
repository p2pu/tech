# Technology at P2PU

To execute our mission we develop and maintain several software tools. This document serves as an index for all the tools and projects we're working on. For things we've developed, this document will contain a link to the GitHub repo. The README file in that repo contains the project specific documentation.

At the end of the document there are links to some meta-level documentation/

## What we’re working on
 - The [general prioritized](https://github.com/orgs/p2pu/projects/4) project contains GitHub issues we are working on right now.
 - We keep [notes of our weekly tech call](https://docs.google.com/document/d/17ZWndqIlppfHWPfhSi3jkwOZytJSpZaM6a3ZgVoXIRA/edit) 
 - The [P2PU Roadmap](https://docs.google.com/document/d/1RHfv68siEVY2R1VpFtTjW74NkguQnbvaz-zJeACe8jg/edit) shows, short and medium term plans for the whole of P2PU
 - The [Google drive folder](https://drive.google.com/drive/u/1/folders/0B7og5r-ukGUiMnJlaEtUZ0FJNjA) contains several documents that may not be listed here.

## Overview

The most important projects are we working on on a regular basis are the P2PU home page and learning circles. The homepage provides a robust frontend for users while learning circles provides an API for the interactive parts of the P2PU home page. Many of the other active projects are extensions of this or components that forms a part of it.

![diagram of services](tech-overview.svg)

### Active projects
- P2PU homepage: [GitHub](https://github.com/p2pu/p2pu-website/)
- Learning circles: [GitHub](https://github.com/p2pu/learning-circles/)
- Team pages: [GitHub](https://github.com/p2pu/erasmus-partner-site/)
- Course-in-a-box: [GitHub](https://github.com/p2pu/course-in-a-box/)
- p2pu-components: [GitHub](https://github.com/p2pu/p2pu-components/)
- p2pu-theme: [GitHub](https://github.com/p2pu/p2pu-theme)
- Wordpress theme: [GitHub](https://github.com/p2pu/P2PUfourteen-wp-theme)

### 3rd Party
- Wordpress - we use a Wordpress instance hosted on Dreamhost
- Discourse - we host a discourse forum for discussion in our community. See [marvin/community.yml](https://github.com/p2pu/marvin/blob/master/community.yml) for details on how it is set up.
- Etherpad - we also run a etherpad-lite instance for short-lived notes. See [marvin](https://github.com/p2pu/marvin/)

### Legacy
- Lernanta - [GitHub](https://github.com/p2pu/lernanta)
- Badges - [GitHub](https://github.com/p2pu/badges)
- Mechanical MOOC - [GitHub](https://github.com/p2pu/mechanical-mooc)
- Archive - [GitHub](https://github.com/p2pu/archive)
- Reports - [GitHub](https://github.com/p2pu/reports)
- Data - [GitHub](https://github.com/p2pu/data)
- Discourse - https://discourse.p2pu.org

## Guides and best practices
P2PU dev checklist
- [Development guide](https://docs.google.com/document/d/1aoQ8leLNKbUdCN-SGWLNkZOfwOQ2kWKBV6H0hnwPQvQ/edit)
- [Sysadmin guide](https://docs.google.com/document/d/1e8tZoo7BrZYygBEgirtBeK4wjJOdE2LvSkajgEOeojs/edit)
- Voice and tone
- [Design guidelines and assets](https://github.com/p2pu/design)
- [Notes on EdTech tools](https://github.com/p2pu/notes-on-edtech)
- [Tech strategy](https://docs.google.com/document/d/1zHow9ohcAIPVibsgzvuWv0Pcca6XNwQ2SrdNhfGswo0/edit#)
- [Learning Circle tools](https://docs.google.com/document/d/15bH1j5BF5sFDGFbMs0a9nvFAHkVc8MUSlOPIsx4CnNM/edit#heading=h.tk6kvxcllzvg)
- How we know it works
   - We are achieving desired P2PU outcomes
   - People are using what we build and host
      - Google Analytics
      - https://p2pu-furrystats.herokuapp.com/
   - People are talking about what we build
      - [Tech Impact](https://docs.google.com/spreadsheets/d/1-Zgwm4xBvhnv_jWynPm9PsMmPpJx4jswC2FyNuCPRw4/edit#gid=0)
   - People are repurposing what we build
      - [GitHub repos + forks](https://docs.google.com/spreadsheets/d/1aPj2Xv6mUSxLN-FTlnZEH60ioF5vhbbgBNA0_-wLjWE/edit#gid=0)
