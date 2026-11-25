# Organica

### Personal Task Manager

**Organize naturally. Focus intentionally.**

---

Organica is a personal task management system concept designed to bring clarity to everyday activities, priorities and commitments.

Built around simplicity, flexibility and thoughtful design, its goal is to make personal organization feel natural — without adding unnecessary complexity.

> **Project focus:** Software Engineering · Software Architecture · Requirements Analysis · Human-Centered Design

---

## Contents

- [Overview](#overview)
- [Vision & Philosophy](#vision--philosophy)
- [Core Features](#core-features)
- [Conceptual Structure](#conceptual-structure)
- [Task Management](#task-management)
- [Engineering Focus](#engineering-focus)

---

## Overview

Organica starts from a personal need: having a clear and intuitive space to organize activities, manage deadlines and keep track of personal goals.

The concept is based on a flexible task management environment where activities can exist independently or be grouped into optional projects.

Organica is designed around the idea that personal organization should support everyday life rather than become another source of complexity.

As a software engineering case study, Organica explores:

- Requirements analysis and specification.
- Domain modeling and task relationships.
- Software architecture and design decisions.
- Data modeling and persistence concepts.
- Maintainability and extensibility.
- Human-centered software design.

The project focuses on the engineering and design of the system rather than its full implementation.

---

## Vision & Philosophy

### Organize without adding complexity.

Organica aims to provide a straightforward environment where users can manage their activities without being overwhelmed by unnecessary features or complicated workflows.

Its design is guided by three principles:

| Principle | Purpose |
|:--|:--|
| **Simplicity** | Keep task management clear and straightforward. |
| **Flexibility** | Adapt to different organizational needs. |
| **Clarity** | Make priorities, deadlines and progress easy to understand. |

The goal is not simply to manage tasks, but to make personal organization more natural and intentional.

---

## Core Features

The system concept includes the following capabilities:

- Create, edit and delete tasks.
- Add titles and descriptions.
- Set priorities and deadlines.
- Track progress through task statuses.
- Organize tasks into optional projects.
- Filter and sort activities.
- View relevant activities and upcoming deadlines.
- Access a general overview of personal tasks.

These capabilities define the functional scope of the conceptual system.

---

## Conceptual Structure

Organica is organized around three main areas, each offering a different perspective on the same set of activities.

### 01 — Overview

A general dashboard highlighting relevant activities, upcoming deadlines, priorities and overall progress.

The overview provides a concise understanding of the user's current commitments.

### 02 — My Tasks

A complete view of personal tasks, including both independent activities and tasks associated with projects.

Tasks can be filtered and sorted according to different criteria, such as priority, deadline or status.

### 03 — Projects

A dedicated area for organizing activities into projects.

Each project represents a group of related tasks and provides a focused view of the activities associated with it.

**Projects are optional.** Tasks can exist independently without belonging to any project.

This distinction is central to the domain model: a task does not require a project to be meaningful.

---

## Task Management

Each task is defined through a small set of essential attributes.

| Attribute | Description |
|:--|:--|
| **Title** | A short description of the activity. |
| **Description** | Additional information about the task. |
| **Priority** | An indication of its importance. |
| **Deadline** | The expected completion date. |
| **Status** | The current state of the task. |
| **Project** | An optional association with a project. |

### Task Statuses

The task workflow includes three states:

`To Do` → `In Progress` → `Completed`

This structure provides enough flexibility for everyday task management while keeping the workflow straightforward.

The status model also provides a basis for analyzing valid transitions and the representation of completed or overdue tasks.

---

## Engineering Focus

Organica provides a focused context for exploring the engineering decisions behind a relatively simple application domain.

### Requirements Engineering

Define the problem, identify stakeholders and establish functional and non-functional requirements.

### Domain Modeling

Identify the main domain entities, their attributes, relationships and constraints.

### Software Architecture

Evaluate architectural alternatives and define a structure that supports clarity, maintainability and appropriate separation of responsibilities.

### Data Modeling

Explore how tasks, projects and their relationships can be represented and persisted.

### Quality Attributes

Consider usability, reliability, maintainability, performance and other relevant quality attributes.

### Verification Strategy

Define how requirements and design decisions can be evaluated through suitable verification and validation techniques.

---

<sub>A software engineering case study exploring task management, software architecture and human-centered technology.</sub>
