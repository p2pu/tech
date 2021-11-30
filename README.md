# Technology at P2PU

This document provides an overview for anyone interested in using or contributing to the software tools we develop and host at P2PU. Detailed documentation for each project resides in its GitHub respository.

At the end of the document, there are links to some meta-level documentation.

## Overview

The most important projects are we working on on a regular basis are the P2PU home page and learning circles. The homepage provides a robust frontend for users while learning circles provides an API for the interactive parts of the P2PU home page. Many of the other active projects are extensions of this or components that forms a part of it.

![diagram of services](tech-overview.svg)

### Active projects
- **P2PU homepage** ([GitHub](https://github.com/p2pu/p2pu-website/)) ([www.p2pu.org](https://www.p2pu.org)). This is our home on the web aimed at both learners and facilitators. It also contains information about P2PU as an org.
- **Learning circles** ([GitHub](https://github.com/p2pu/learning-circles/)) ([learningcircles.p2pu.org](https://learningcircles.p2pu.org)). Implements the logic and backend for our learning circles management system. This includes facilitator and organizer dashboard, learning circle management pages and team stats/management pages. It also provides an API that is used by the home page and team pages. 
- **Team pages** ([GitHub](https://github.com/p2pu/erasmus-partner-site/)). These micro-sites give an opportunity for teams to contextualize learning circles for participants and facilitators. It also integrates with the API.
- **Course-in-a-box** ([GitHub](https://github.com/p2pu/course-in-a-box/)) ([course-in-a-box.p2pu.org](https://course-in-a-box.p2pu.org)). Our internal, but also shared, tool for creating course-like sites.
- **p2pu-components** ([GitHub](https://github.com/p2pu/p2pu-components/)). This is a component library that we use to build our interactive React frontends.
- **p2pu-theme** ([GitHub](https://github.com/p2pu/p2pu-theme)). This is our customized Bootstrap theme used on all our web properties. 
- **Wordpress theme** ([GitHub](https://github.com/p2pu/P2PUfourteen-wp-theme)). Our custom Wordpress theme that utilizes p2pu-theme.

### 3rd Party
- **Wordpress** ([info.p2pu.org](https://info.p2pu.org)) - we use a Wordpress instance hosted on Dreamhost
- **Discourse** ([community.p2pu.org](https://community.p2pu.org))- we host a discourse forum for discussion in our community. See [marvin/community.yml](https://github.com/p2pu/marvin/blob/master/community.yml) for details on how it is set up.
- **Etherpad** ([etherpad.p2pu.org](https://etherpad.p2pu.org)) - we also run a etherpad-lite instance for short-lived notes. See [marvin](https://github.com/p2pu/marvin/)

### Legacy
- **Lernanta** ([GitHub](https://github.com/p2pu/lernanta)) ([courses.p2pu.org](https://courses.p2pu.org)) - An old course platform we've build. We're still hosting it as a Django app, but we'll transform it to static pages at some stage.
- **Course forum** ([discourse.p2pu.org](https://discourse.p2pu.org)) - Discourse forum for course discussions.
- **Badges** ([GitHub](https://github.com/p2pu/badges)) ((badges.p2pu.org)(https://badges.p2pu.org)) - A badge platform for project based learning.
- **Mechanical MOOC** ([GitHub](https://github.com/p2pu/mechanical-mooc)) ([mechanicalmooc.org](http://mechanicalmooc.org)) - Old experiement in running a low cost MOOC. It was good at sequencing content.
- **Archive** ([GitHub](https://github.com/p2pu/archive)) ([archive.p2pu.org](https://archive.p2pu.org/)) - Drupal applications used to run courses. Hosted as static files.
- **Reports** ([GitHub](https://github.com/p2pu/reports)) ([reports.p2pu.org](https://reports.p2pu.org/)) - Takeaways from things P2PU did in the past.
- **Data** ([GitHub](https://github.com/p2pu/data)) ([data.p2pu.org](https://data.p2pu.org)) - Anonymised data shared for research purposes.

## Guides and best practices
- [Tech strategy](https://docs.google.com/document/d/1zHow9ohcAIPVibsgzvuWv0Pcca6XNwQ2SrdNhfGswo0/edit#)
- [Learning Circle tools](https://docs.google.com/document/d/15bH1j5BF5sFDGFbMs0a9nvFAHkVc8MUSlOPIsx4CnNM/edit#heading=h.tk6kvxcllzvg)
- [Development guide](https://docs.google.com/document/d/1aoQ8leLNKbUdCN-SGWLNkZOfwOQ2kWKBV6H0hnwPQvQ/edit)
- [Sysadmin guide](https://docs.google.com/document/d/1e8tZoo7BrZYygBEgirtBeK4wjJOdE2LvSkajgEOeojs/edit)
- [Voice and tone](https://docs.google.com/document/d/1v7UiCw9i0sE6XcxxhgCJUs97-1gxV2Gsky1BOMQ_b5w/edit)
- [Design guidelines and assets](https://github.com/p2pu/design)
