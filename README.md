# 🚀 SP + CD Diagnostic Dashboard — Internship Project

The **Sponsored Products + Onsite Display Diagnostic Dashboard** is an internal developer tool designed to help engineers and technical support teams better understand why certain SKUs are delivered (or excluded) during the ad auction process.

This project improves visibility into:

- Auction outcomes
- SKU eligibility and filtering
- Campaign and creative metadata
- Line item delivery behavior

All without needing to manually query services or logs.

---

## 🎯 Project Goal

The primary goal of this project was to:

> Build an internal diagnostic page that exposes key auction, campaign, and SKU-level insights — without requiring manual data lookups or external debugging tools.

The page helps teams:

✔ Investigate auction & delivery results  
✔ Understand SKU-level filtering and eligibility  
✔ View placement, campaign, and creative information in one place  
✔ Reduce time spent analyzing logs or tracing pipeline behavior  

While the dashboard covers common scenarios, it is intentionally designed to support future extensions and new delivery models.

---

## 🧠 What I Learned During the Project

This project helped me:

- Deeply understand the ad delivery and auction pipeline
- Work within a large production codebase and service architecture
- Build strongly-typed diagnostic models in C#
- Work with Razor Pages and Bootstrap UI components
- Translate backend logic into visual debugging tools
- Collaborate with engineers and product partners

It was a great mix of:

> backend diagnostics, data interpretation, and developer tooling.

---

## 🛠️ Key Features I Implemented

### ✅ Placement & Line-Item Accordion View

- Groups placements logically
- Separates Sponsored Products and Onsite Display
- Expands down to individual line items and SKU data

---

### 🟢 Visual Delivery Indicators

Delivery state is clearly shown using UI signals:

- Green states indicate delivered SKUs
- Grey states indicate filtered / not delivered

This allows faster scanning and interpretation.

---

### 📦 SKU Results Explorer

For each line item, the dashboard:

- Iterates over all SKUs without duplication
- Separates Delivered vs Ineligible SKUs
- Displays SKU metadata
- Provides modal pop-ups with full details, including:

  - SKU ID and key
  - Product attributes
  - Advertiser and taxonomy identifiers
  - Quantity and pricing
  - Rendering and culture attributes

Developers can now inspect SKU context with a single click.

---

### 🧩 Campaign, Creative & Account Information Panels

Data is organized into readable “section card” panels, including:

- Campaign information and buy type
- Line item configuration
- Creative format metadata
- Account and advertiser identifiers

This reduces the need to cross-reference external tools.

---

### 💬 Tooltips & Contextual Debugging Hints

Added:

- tooltips for domain-specific terminology
- contextual explanations
- diagnostic guidance for auction behavior

This improves onboarding and knowledge transfer across teams.

---

## 🎥 Demo

A video walkthrough will be added here.

_(Placeholder area reserved for project demo video.)_

---

## 🧩 Tech Stack

Built using:

- ASP.NET Razor Pages
- C#
- Strongly-typed backend models
- Bootstrap Components
- Accordion + Modal UI Patterns

Designed specifically for internal diagnostics and engineering workflows.

---

## 🚦 Impact

This dashboard improves debugging efficiency by:

✨ Reducing manual queries and log inspection  
✨ Centralizing visibility into delivery outcomes  
✨ Making SKU eligibility easier to interpret  
✨ Supporting faster hypothesis testing  
✨ Improving onboarding for new engineers

Instead of:

> Manually tracing auction logic across multiple services

Teams can now:

> Open the diagnostic dashboard and view answers immediately.

---

## 🎉 Acknowledgements

This project was developed during my internship with guidance, feedback, and collaboration from the engineering team.

I’m grateful to everyone who helped review code, explain pipeline logic, and share domain knowledge throughout this project.

---

