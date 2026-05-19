# Vigil
# 🫀 Vigil
### *Because someone should always know.*

> Real-time ER communication for patients, families, and staff.

Built for the **Build with MeDo Hackathon 2026** · #BuiltWithMeDo

---

## The Story

Eight hours.

That's how long we sat in that waiting room. Eight hours with no updates, no answers, no one coming through those doors to tell us anything. Eight hours of watching strangers walk in and out while we didn't know if our best friend was alive.

The last thing we heard before they took her back was her crying. And a surgeon saying the words **life or death.**

Then silence. For eight hours.

When she finally made it through, we learned that a critical detail had slipped between staff during a shift change. Gone. Because there was no system to catch it.

The problem wasn't the doctors. It wasn't the nurses. **It was the silence.**

No visibility for patients. No connection for families. No continuity between staff. People doing their best inside a broken system — and the people who love them left completely in the dark.

We built Vigil because someone should always know.

---

## What It Does

Vigil is a real-time ER communication platform with three connected experiences:

### 🔵 For Patients
- See your position in the queue
- Track every update in your care timeline
- Know exactly what's coming next — in plain language, no jargon

### 🟢 For Families
- Receive a private share link the moment your loved one checks in
- See live status updates from anywhere — no app download, no login required
- Never sit in a waiting room wondering again

### 🟡 For Staff
- Log patient updates in seconds through a simple chat interface
- Color-coded urgency dashboard (🟢 stable / 🟡 monitor / 🔴 critical)
- **One-click AI Summary** — instantly generates a full plain-English care history so any new nurse or doctor is up to speed before they walk in
- **Smart escalation alerts** — automatically flags any patient with no update in 60+ minutes
- **AI intake form** — conversational chat at arrival captures symptoms, pain level, allergies, and medications, automatically seeding the staff summary from minute one

🌐 **Language support:** English, Spanish, and Chinese — because ERs serve everyone.

---

## Key Features

| Feature | Description |
|---|---|
| 🤖 AI Handoff Summary | One button generates a full plain-English care history for incoming staff |
| 🔗 Family Share Link | Private, no-login link sent to family at check-in |
| 🚨 Escalation Alerts | Auto-flags patients with no update in 60+ minutes |
| 💬 AI Intake Form | Conversational intake that seeds the staff summary from arrival |
| 🌐 Multilingual | English, Spanish, and Chinese support |
| 🎨 Urgency Dashboard | Color-coded patient cards for instant staff prioritization |

---

## How It Was Built

Vigil was built entirely using **[MeDo](https://medo.dev)** through multi-turn conversational prompting — no code written.

We started with the core dual-view architecture and progressively layered each feature through MeDo's chat interface. MeDo's ability to retain context across turns was critical — we could say *"now add a 60-minute escalation alert to the staff dashboard"* and it understood exactly where and how to integrate it without rebuilding anything.

**MeDo features used:**
- Multi-turn chat for iterative feature building
- Full-stack generation for routing data between patient and staff views
- Plugin integrations for multilingual support and shareable links
- Visual editor for UI refinement
- One-click deployment for a live public URL

---

## Challenges

The hardest design challenge was **tone**. A staff dashboard needs to feel urgent and fast. A patient-facing screen needs to feel calm and reassuring. These are opposite design philosophies living inside the same app — getting MeDo to maintain that distinction across both views took careful, deliberate prompting.

The other challenge was the **AI intake → AI summary pipeline** — making sure intake data fed meaningfully into the one-click staff summary rather than just existing as a separate data point.

---

## What We're Proud Of

I never thought I could build something like this. I'm not a developer. I don't write code. But I kept thinking about those eight hours and I couldn't just do nothing.

The **AI handoff summary** is the one that gets me. One button. A nurse walks in, hits it, and instantly knows everything. That's the exact moment that failed my friend. The fact that we built something that could have changed that night for her — I don't have words for that.

The **family share link** looks small on paper. But that's me, sitting in that waiting room, staring at my phone with nothing. That feature is for every person who has ever sat where I sat.

And honestly — the thing I'm most proud of is that this is a real story. Not a hackathon idea. Not a hypothetical problem. This is my best friend's life. And now it's an app that could help someone else's.

---

## What's Next

- **EHR integration** — connecting with hospital electronic health record systems
- **SMS & push notifications** for families not actively watching the app
- **Voice logging** for staff — speak an update instead of typing it
- **Analytics dashboard** for hospital administrators to identify bottlenecks
- **Expanded language support** — French, Arabic, and Portuguese

---

## Built With

- [MeDo](https://medo.dev) — AI-powered full-stack app builder by Baidu
- ERNIE AI (via MeDo)
- Zero lines of code written

---

*Vigil started with one person's story. Eight hours of silence that never should have happened.*

*The goal is to make that silence impossible for anyone else.*

---

Built by Lilly · [#BuiltWithMeDo](https://medo.devpost.com) · Build with MeDo Hackathon 2026
