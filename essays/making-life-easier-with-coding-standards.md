---
layout: essay
type: essay
title: "Making Life Easier with Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2022-09-21
published: true
labels:
- ESLint
- Coding Standards
- Learning
---

Imagine an alternate universe where coding standards do not exist. Tech giants have a colossal blob of code for each of their applications. Typos everywhere, misaligned lines, variables being declared and not being used, missing semicolons where they are needed, and the list goes on. Now imagine what it would be like in the office. Coworkers arguing about whether using single quotes is superior to double quotes. Engineers working 100-hour weeks and ripping out their hair trying to figure out each other's code. This hyperbole is how I see the world without coding standards.

#### Now, what exactly are coding standards?
They are stylistic rules set by conventions or organizations to provide consistency in code structure. Coding standards can improve the workflow of software engineers because they make code more legible, which in turn makes debugging easier for teams. An analogy to coding standards is writing styles such as APA, MLA, etc. These associations have guidelines on the structure of a paper, and it varies from field to field. The same goes for programming, where coding standards differ between certain languages or between organizations.

#### Reducing pain with ESLint
ESLint is every web developer’s best friend once they learn about it. It is a Javascript linter that analyzes code to ensure that style rules are followed. The style rules can be implemented by the user via the ESLint configuration file, which can be useful when working with teams. This linter also can come with built-in presets when you install it such as the popular AirBnB style guide. When there are inconsistencies between the code and the style settings, the code will be flagged. This can mediate a lot of the pain associated with code readability and debugging other people’s code.
