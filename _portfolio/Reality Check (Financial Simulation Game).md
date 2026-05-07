---
title: "Reality Check (Financial Simulation Game)"
excerpt: "A personal finance simulation game where players navigate real-world budget decisions across 30 days — balancing income, expenses, savings, and happiness."

header:
  overlay_image: "/assets/images/RealityCheck/RealityCheck_Header.png"
  teaser: "/assets/images/RealityCheck/RealityCheck_Header.png"
  overlay_filter: 0.5

project_brief: "A Unity-based simulation game designed to teach financial literacy through consequence-driven decision making."
project_role: "Game Designer / Developer"
project_tools: "Unity, C#, TextMeshPro"
project_date: "2026"

realitycheck_gallery:
  - url: /assets/images/RealityCheck/RealityCheck_1.png
    image_path: /assets/images/RealityCheck/RealityCheck_1.png
    alt: "Budget setup screen"
  - url: /assets/images/RealityCheck/RealityCheck_2.png
    image_path: /assets/images/RealityCheck/RealityCheck_2.png
    alt: "Event decision screen"
  - url: /assets/images/RealityCheck/RealityCheck_3.png
    image_path: /assets/images/RealityCheck/RealityCheck_3.png
    alt: "Stats and balance tracking UI"
  - url: /assets/images/RealityCheck/RealityCheck_4.png
    image_path: /assets/images/RealityCheck/RealityCheck_4.png
    alt: "Game over and score screen"
---

## Overview

Reality Check is a financial simulation game built in Unity that puts players inside the pressure of everyday money decisions. Players set their own starting budget — income, rent, food, utilities — then navigate 30 days of randomized life events that test how well they can balance competing financial and emotional priorities.

The core question the game asks is simple: when money is tight, what do you sacrifice first?

Every event forces a tradeoff between Balance, Savings, and Happiness. There is rarely a free win. A car breakdown, a friend's birthday dinner, an unexpected medical bill — each one pulls the player in a different direction and reflects the kind of decisions real people face every month.

---

## Gallery

{% include gallery id="realitycheck_gallery" %}

---

## Design Focus

Reality Check was built around one core insight: most people learn financial decision-making by making mistakes with real money. This game creates a consequence-driven environment where those lessons are low-stakes but still feel meaningful.

Key design goals included:

- **Personalized starting conditions** so the game reflects the player's actual financial situation rather than an abstract scenario
- **No clearly correct choices** — every event is designed to have a real tradeoff so players can't just optimize their way through
- **Three-resource tension** between Balance, Savings, and Happiness to mirror how financial stress affects wellbeing, not just bank accounts
- **Weekly income and expense cycles** that simulate the paycheck-to-paycheck rhythm many people actually live with
- **Score and ranking system** to give players a sense of progress and replayability

---

## Development

Reality Check was developed as an MVP prototype for a class venture project. The game was built in Unity using C# with a modular event system that separates game logic, UI management, and event data — making it straightforward to expand the event pool without touching core systems.

The event architecture uses a daily pool system that prevents repeated scenarios within the same day, keeping the experience varied across a full playthrough. The UI manager handles all visual feedback including stat flashing, weekly bill warnings, and color-coded choice previews.

Iteration focused on balancing the economy so that players who make reasonable decisions can survive, while players who ignore savings or happiness face meaningful consequences before the 30 days are up.

---

## Resources

<iframe frameborder="0" src="https://itch.io/embed/4552381?border_width=5&amp;bg_color=00270b&amp;fg_color=ffffff&amp;link_color=4a5ecb&amp;border_color=31552e" width="560" height="175"><a href="https://jc1014.itch.io/reality-check">Reality Check Budgeting Simulator by Zenith</a></iframe>