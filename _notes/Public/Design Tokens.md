---
title: Design Tokens
notetype : lit
date: 2021-02-05
---

Design tokens are the “subatomic” foundation of a [[Design System]] implementation. They are the values needed to build a design system, like color, space, typography etc., **represented as data.**

#### Design token types

- **Global tokens**
	- Global tokens values, represented by context-agnostic names.
	- Eg : Hex value represented as Gray-100

- **Alias tokens**
- Alias tokens relate to a specific context, making purpose/context easier to identify. 
- Eg : Gray-100 represented as bg-color

- **Component-specific tokens**
	- representation of value associated with a component.
	- Eg : bg-color, represented as primary-button-cta-color

- In case of system that supports multiple screen sizes, we can build global tokens anchored around base values of each screen sizes. 
- Eg : Adobe Spectrum Size tokens (size-100 means 100%, 8px on desktop and 10px on mobile )

**Sources** 
- [[Book- Design Systems Handbook]] 
- [Adobe Spectrum ](https://spectrum.adobe.com/page/design-tokens/)

#🌱def / [[§Design]]