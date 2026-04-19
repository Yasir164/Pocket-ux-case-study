# Pocket — UX Case Study

### Personal Finance & Budgeting App for Everyone

![Platform](https://img.shields.io/badge/Platform-iOS%20%2B%20Responsive%20Web-1A6BB5)
![Tools](https://img.shields.io/badge/Tools-Figma-4CAF7D)
![Status](https://img.shields.io/badge/Status-Hi--fi%20Complete-brightgreen)
![Duration](https://img.shields.io/badge/Duration-April%20–%20June%202026-1A6BB5)

---

## Overview

Pocket is a mobile app and responsive website designed to solve a universal problem — not knowing where your money goes. Whether you are a university student making a weekly allowance last the month, a young professional who earns well but saves nothing, a freelancer with variable income, a couple managing shared expenses, or a retiree living on a fixed pension — Pocket provides a fast, flexible, and visually clear budgeting experience that adapts to how you actually earn and spend.

**Role:** Lead UX Designer and UX Researcher — end-to-end design across research, wireframing, visual design, and prototyping.

---

## The Problem

Personal finance is one of the most universal challenges people face, yet existing tools consistently fail large segments of the population. The core problem is not a lack of financial apps — it is that every existing app is built for one type of user: a salaried adult with a stable monthly income and time to set up a complex budgeting system.

**Three major user groups are completely underserved:**

- **Students and irregular earners** — income arrives weekly or unpredictably; monthly-salary apps are structurally incompatible with their lives
- **Couples and shared households** — need shared financial visibility but are forced to pay premium prices or manage everything manually
- **Older users and retirees** — managing a finite fixed income, not growing savings — invisible in every competitor's product

---

## The Solution

Pocket adapts to how users actually earn money. The core solution is built around five pillars:

1. **Income mode selector** — At onboarding users choose: Salary, Allowance, Freelance, or Pension. This sets the entire budgeting model
2. **Visual spending dashboard** — Chart-first view showing category breakdown and monthly progress at a glance
3. **Two-tap expense entry** — Log any expense in under 5 seconds
4. **Savings goal tracker** — Visual progress bars with auto-transfer option
5. **Smart contextual alerts** — Spending warnings with suggested next action, not just passive notifications

---

## Design Process

### Empathize

Research conducted through user interviews, surveys, and secondary research. Five personas developed representing distinct financial situations:

| Persona | Age | Occupation | Location | Core Challenge |
|---|---|---|---|---|
| Maya Chen | 26 | Software Engineer | Taipei, Taiwan | Earns well, has no idea where money goes |
| James Okafor | 22 | University Student | Lagos, Nigeria | Allowance runs out before month end |
| Sarah Mitchell | 34 | Freelance Designer | London, UK | Unpredictable income, inconsistent cash flow |
| Ravi & Priya Sharma | 31/29 | Product Manager / Teacher | Mumbai, India | No free shared budget tool exists |
| Eleanor Hayes | 68 | Retired Teacher | Edinburgh, UK | Fixed pension, needs savings runway |

**Key quotes:**
> *"I earn well but I have no idea where my money goes every month."* — Maya Chen

> *"My student allowance runs out before the end of the month and I never see it coming."* — James Okafor

### Define

**Problem statement:** People at every income level and life stage need a budgeting tool that adapts to how they actually earn money — not how finance apps assume they earn money. Monthly-salary apps structurally exclude students, freelancers, couples, and retirees.

**How Might We statements:**
- How might we design onboarding that works for users with irregular income?
- How might we make expense logging so fast that users actually do it?
- How might we offer shared budgeting without requiring a paid subscription?
- How might we help retirees understand how long their savings will last?

### Ideate

Competitive audit of 5 apps: Mint, YNAB, Money Manager, Spendee, Excel/Google Sheets.

**Key finding:** No competitor supports variable or irregular income natively. All assume a monthly salary baseline — structurally excluding students, freelancers, and pension users.

| Feature | Mint | YNAB | Money Manager | Spendee | Pocket Goal |
|---|---|---|---|---|---|
| Variable income | No | Partial | No | No | Yes |
| Onboarding time | 8 min | 18 min | < 2 min | 4 min | < 3 min |
| Shared budget free | No | Paid only | No | Paid only | Free tier |
| Visual dashboard | Strong | Average | Weak | Strong | Strong |
| Offline entry | Partial | Yes | Yes | Yes | Yes |
| Retirement/fixed income | No | No | No | No | Yes |

### Prototype
- Lo-fi wireframes across all core flows
- Hi-fi prototype with full design system in Figma
- Bold red and white color palette — trustworthy, modern, action-oriented
- Responsive website at 3 breakpoints

### Test

**Moderated usability study — 5 participants — 2026**

Identified and prioritized issues across P0 (critical), P1 (important), and P2 (roadmap) categories.

---

## Usability Testing Results

### P0 — Critical (must fix before launch)

**1. Onboarding confusion at income mode step**
- 3 of 5 participants did not understand what 'Allowance' or 'Freelance' meant in context
- 2 participants abandoned onboarding before reaching the dashboard
- P2 asked "What happens if I pick the wrong one?" — P1 said "I'm not sure which one I am"
- **Fix:** Add plain-English description under each option + "You can change this later" reassurance label + make mode editable from Profile settings

**2. Two-tap expense entry failed for first-time users**
- All 5 participants missed the floating action button (FAB) for adding an expense
- P4 scrolled up and down the dashboard looking for "add" or "log"
- P5 tapped the chart expecting it to open a form
- **Fix:** Replace FAB with a prominent sticky "Add expense" button above the nav bar + tooltip on first launch

### P1 — Important improvements

**3. Budget category labels too generic**
- Users could not map their real spending to default categories
- **Fix:** Allow users to rename and create custom budget categories during setup

### Strengths — Preserve
- Visual chart-first dashboard consistently praised for clarity
- Income mode concept resonated strongly once explained — all participants understood the value

---

## Key Screens

### Mobile App

| Flow | Screens |
|---|---|
| Onboarding | Splash · Income mode · Goal setup · Sign up |
| Dashboard | Home · Spending overview · Category breakdown |
| Transactions | Add expense · Transaction history · Search & filter |
| Budget | Budget setup · Category management · Alerts |
| Goals | Goals overview · Goal detail · Add goal |
| Shared | Couple mode · Split view |
| Profile | Settings · Notifications · Export report |

### Responsive Website

Landing · Sign up · Log in · Dashboard · Transactions · Budget · Goals · Reports · Settings

---

## Key Design Decisions

**1. Income mode selector at onboarding**
The single most important UX decision in the project. By asking how users earn money upfront, the entire app adapts — freelancers get weekly budget cycles, students get allowance tracking, retirees get savings runway calculators. No competitor does this.

**2. Two-tap expense entry — revised post-testing**
Original design used a floating action button that 5/5 participants missed. Revised to a prominent sticky "Add expense" button above the nav bar — directly addressing the P0 usability finding.

**3. Shared budget as a free feature**
Every competitor locks shared mode behind a paid plan. Pocket offers it free — a direct response to the competitive audit finding that couples are entirely excluded from the free tier everywhere.

**4. Chart-first dashboard**
No raw numbers on the home screen. The first thing users see is a visual spending breakdown — instantly readable regardless of financial literacy level.

---

## Color Palette

| Role | Hex | Usage |
|---|---|---|
| Primary red | `#E53935` | Buttons, active states, key CTAs |
| Dark navy | `#1A1A2E` | Headers, primary text |
| Light grey | `#F5F5F5` | Backgrounds, card surfaces |
| Success green | `#4CAF7D` | Savings goals met, positive trends |
| Warning amber | `#FF9800` | Budget warnings, overspend alerts |

**Typography:** Inter — clean, legible, modern financial feel at all text sizes

---

## Tools Used

- **Figma** — wireframing, hi-fi design, prototyping, component library
- **UX Research** — personas, user journey maps, competitive audit, prioritized insights document
- **Usability Testing** — moderated sessions with 5 participants

---

## View Prototype

[View Pocket Mobile Prototype on Figma](https://www.figma.com/design/JTCcR8l4k6BcEU3Ns2q5tr/Project-2-Pocket-app?node-id=15-507&embed-host=share)

[View Pocket Website Prototype on Figma](https://www.figma.com/design/JTCcR8l4k6BcEU3Ns2q5tr/Project-2-Pocket-app?node-id=2-7&embed-host=share)

---

## Designer

**Yasir Afaque**
MTech in Engineering — National Kaohsiung Normal University, Taiwan
Google UX Design Professional Certificate — 2026
MOE Taiwan Scholarship Recipient

[Portfolio](https://github.com/Yasir164) · [LinkedIn](https://www.linkedin.com/in/yasir-afaque-9472751a1/) · [Figma](https://www.figma.com/team_invite/redeem/eJNiDvaHPvUX0hwoBgawoZ?t=lSJO0qMrZdWV7MR0-21)

