# Prisma

**A Creative Space for Artists**  
*Create. Discover. Get Inspired.*

---

Prisma is a creative discovery platform concept designed to connect artists, creative works and people looking for inspiration.

The platform explores a space where users can publish, discover and appreciate different forms of artistic expression, including images, videos, music and written content.

Rather than focusing on conversations and traditional social networking interactions, Prisma places creative works at the center of the experience.

> **Project focus:** Software Engineering · Software Architecture · Digital Creativity · Content Discovery

---

## Contents

- [Overview](#overview)
- [Vision & Philosophy](#vision--philosophy)
- [User Experience](#user-experience)
- [Core Features](#core-features)
- [Content & Publishing](#content--publishing)
- [Artist Profiles](#artist-profiles)
- [Content Organization](#content-organization)
- [Topics & Tags](#topics--tags)
- [Discovery System](#discovery-system)
- [Conceptual Structure](#conceptual-structure)
- [Engineering Focus](#engineering-focus)

---

## Overview

Prisma starts from a simple idea: creating a digital environment where creativity can be shared, discovered and appreciated.

It brings together people with different artistic interests, allowing them to publish their work, explore new forms of expression and discover creators they might not otherwise encounter.

The experience is primarily centered around artistic content rather than conversations or personal interactions.

The platform aims to combine content discovery with the expressive freedom of a customizable creative portfolio.

As a software engineering case study, Prisma explores:

- Requirements engineering.
- Flexible and extensible architecture.
- Digital content management.
- Artist identity and profile modeling.
- Personalized content discovery.
- Content organization and relationships.
- Quality attributes of content-centered systems.

The project focuses on the analysis and design of the system rather than its full implementation.

---

## Vision & Philosophy

> *Put creativity at the center.*

Prisma aims to create an environment where artistic expression takes priority over traditional social networking dynamics.

Its design is guided by three principles:

| Principle | Purpose |
|:--|:--|
| **Creativity** | Encourage artistic expression and content creation. |
| **Discovery** | Help users explore different artists, styles and creative works. |
| **Inspiration** | Make it easier to find and appreciate content from different creative fields. |

The objective is to give visibility to both established and emerging creators, while allowing every artist to develop an individual creative identity.

---

## User Experience

> *One platform, two ways to participate.*

All users can participate in both content creation and content discovery.

The concepts of Viewer, Creator and Hybrid represent different ways of using Prisma rather than separate account types.

Every user can freely switch between discovering creative works and publishing their own.

Social interaction is intentionally limited, keeping the focus on artistic content.

---

## Core Features

The system concept includes:

- Create and manage a personal artist profile.
- Publish artistic content.
- Explore creative works from different categories.
- Follow other artists.
- Upvote publications.
- Save publications for later.
- Organize publications into folders and subfolders.
- Customize personal artist profiles.
- Define public and private collections.
- Build custom pages through visual configuration.
- Explore personalized pages using web technologies.
- Select preferred topics during onboarding.
- Discover content through personalized recommendations.
- Browse publications from followed artists.

Comments and direct social conversations are not part of the defined core experience.

---

## Content & Publishing

The concept focuses on four main content categories.

| Category | Description |
|:--|:--|
| **Images** | Photographs, illustrations, drawings and visual artwork. |
| **Videos** | Video creations and audiovisual content. |
| **Music** | Beats, songs, compositions and other musical works. |
| **Texts** | Poetry, stories, lyrics and written creations. |

Small interactive games and other forms of creative content can be considered as extensions of the content model.

Publishing allows creators to present their work while maintaining its artistic identity.

---

## Artist Profiles

> *A portfolio first, a social profile second.*

Each artist has a personal page combining elements of a traditional social profile with the flexibility of a customizable portfolio.

The profile serves as the artist's personal space within Prisma, allowing visitors to explore their creative identity and published works.

Artists can personalize their pages through two conceptual approaches.

### Visual Customization

A visual configuration model that allows users to customize their pages without programming knowledge.

### Custom Web Development

The possibility of developing a more extensively personalized page using web technologies, giving technically skilled artists greater freedom over their presentation.

The conceptual profile may include:

- Personal information and artist identity.
- Published content.
- Followers and following information.
- Customizable layouts and visual elements.
- Personalized portfolio sections.

The objective is to give artists control over how their creative identity is presented.

---

## Content Organization

> *Organize creativity your own way.*

Artists can organize their publications through a hierarchical folder system.

Folders and subfolders allow creators to group their works according to personal preferences, artistic disciplines, projects or other organizational criteria.

Each folder may have its own visibility setting.

| Visibility | Description |
|:--|:--|
| **Private** | Only the owner can access the folder. |
| **Public** | The folder can be explored by other users as part of the artist's portfolio. |

This model combines personal content management with public artistic presentation.

---

## Topics & Tags

> *Connect creative works through shared interests.*

Publications can be associated with multiple topics and tags to improve content organization and discovery.

### Topics

Main categories used to classify creative interests and publications.

Examples:

- Music
- Hip-Hop
- Manga
- Anime
- Illustration
- Photography

### Tags

More specific keywords that describe individual works and help users discover them through targeted searches.

For example, an illustration of Sanji could be associated with:

- **Topics:** Manga, Anime.
- **Tags:** One Piece, Sanji.

This distinction allows publications to be connected to both broad creative categories and specific subjects.

Artists may also introduce additional tags to describe their works more precisely.

---

## Discovery System

Prisma explores two main content discovery areas.

### 01 — Discover

A personalized space for exploring creative works from across the platform.

Users can initially select topics that reflect their interests, helping establish a personalized discovery experience.

A conceptual recommendation model may consider factors such as:

- Selected interests and topics.
- Upvotes.
- Viewed and saved publications.
- Followed artists.
- Content popularity.
- Previous discovery activity.

The system aims to recommend relevant content while occasionally introducing different topics and creative disciplines to encourage exploration.

The recommendation strategy is considered part of the system's architectural design.

### 02 — Following

A dedicated feed containing publications from artists the user follows.

This section provides a direct way to keep up with creators and their latest works.

Together, these two areas balance personalized discovery with the user's existing artistic interests.

---

## Conceptual Structure

The experience revolves around three main areas.

| Section | Purpose |
|:--|:--|
| **Discover** | Explore creative works from across the platform. |
| **Following** | Browse publications from followed artists. |
| **Artist Profile** | Present an artist's identity, portfolio and published content. |

Content publishing, organization and profile customization are considered part of the broader creator experience.

---

## Engineering Focus

Prisma provides a context for exploring content-centered systems and personalized discovery.

### Domain Modeling

Identify the relationships between users, artists, publications, media types, topics, tags, folders and interactions.

### Content Architecture

Analyze how different media types can share common attributes while preserving their specific characteristics.

### Profile Customization

Explore how customizable artist pages can be represented while maintaining clear system boundaries.

### Content Discovery

Evaluate possible approaches to personalized discovery, including explicit interests, user interactions and content metadata.

### Recommendation Design

Consider relevance, diversity, transparency and the potential effects of popularity-based signals.

### Quality Attributes

Evaluate usability, maintainability, extensibility, performance and content discoverability.

---

<sub>A software engineering case study exploring digital creativity and content discovery.</sub>
