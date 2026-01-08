# AuctionDiagnosticTool
🚀 SP + CD Diagnostic Dashboard — Internship Project

Welcome to the Sponsored Products + Onsite Display Diagnostic Dashboard — a tool built to help developers, technical support engineers, and analysts better understand why certain SKUs are delivered (or not!) during the ad auction process.

This project was designed to make internal debugging:

faster ⚡

more visual 🎨

and way less “dig through logs + query everything manually” 🥲

🎯 Project Goal

The goal of this project was to:

Build an internal diagnostic page that exposes key auction, campaign, and SKU-level insights — without requiring manual queries or digging through multiple services.

This page helps teams:

✔ Understand auction & delivery outcomes
✔ Investigate why SKUs were filtered or excluded
✔ View campaign, creative, and targeting metadata in one place
✔ Improve debugging workflows across engineering & TS orgs

While the page handles common diagnostic scenarios, it’s designed to be extensible — future features and new models can be plugged in as needed.

🧠 What I Learned

Working on this project helped me:

Deep-dive into the ad delivery pipeline 🏗️

Understand the organization’s architecture & services

Work with Razor Pages & backend C# models

Interpret auction data, SKU ranking logic, and filtering rules

Collaborate with engineers + product stakeholders

Translate technical logic → usable developer tools

It was a great mix of:

backend reverse engineering + UI diagnosis + developer tooling 🚀

🛠️ Key Features I Implemented
✅ Accordion-based placement breakdown

Groups placements logically

Separates Sponsored Products vs Onsite Display

Expands into line-item level insights

🟢 Visual delivery indicators

Buttons & headers change state based on delivery:

Green = Delivered successfully

Grey = Not delivered / filtered

This makes debugging outcomes easier at a glance.

📦 SKU Results Explorer

For each line item:

Iterates SKUs without duplication

Separates Delivered vs Ineligible SKUs

Displays SKU-level metadata

Opens modal detail panels with:

SKU ID

Product info

Advertiser & taxonomy ids

Quantity, price, attributes, etc.

Developers can now view complete SKU context in one click 🎯

🧩 Campaign, Creative & Account Info Panels

Includes:

Campaign info & buy type

Line item configuration

Creative format metadata

Account information

Organized into clean “section cards” for readability.

💬 Tooltips, UI helpers & diagnostics hints

Added:

tooltips for domain-specific terms

context explanations

debugging hints for auction behavior

This helps reduce tribal knowledge + onboarding friction.

🎥 Demo

(This section is reserved for the project video walkthrough)
📌 Will include a short demo explaining:

problem → solution

architecture overview

feature highlights

🧩 Tech Stack

Built using:

Razor Pages (ASP.NET)

C#

Bootstrap UI components

Modal & accordion components

Strongly-typed diagnostic models

Designed for internal debugging workflows — not public dashboards.

🚦 Impact

This project improves developer + TS pipelines by:

✨ Reducing time spent querying logs
✨ Making delivery outcomes easier to interpret
✨ Improving onboarding for new engineers
✨ Centralizing diagnostic context
✨ Enabling faster hypothesis testing

Instead of:

“Why didn’t this SKU deliver? Let’s look in 5 tools…”

Now it’s:

“Open the diagnostic page — the answer’s right there.” 😎

🎉 Credits

Built during my internship — with mentorship, feedback & support from the team 🤍
Huge thanks to everyone who helped review code, explain pipeline logic, and share domain knowledge
