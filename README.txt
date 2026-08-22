# AstroLive Match 🔮

### Question-first astrologer matching for AstroLive

> **Your question deserves the right astrologer.**

AstroLive Match is a product concept and functional prototype built for **AstroHack 2026**.

The core idea is simple:

**Don't make users browse dozens of astrologers and guess who is right for them. Understand what they are trying to solve, then recommend the best available expert for that specific question.**

---

## 🚀 Live Prototype

👉 **[Open AstroLive Match] https://harshmarc5.github.io/Astrolive_harshvardhan_thakor/
## The Problem

AstroLive already exposes useful information about astrologers:

- Expertise
- Astrology methodology / tradition
- Language
- Experience
- Reviews
- Availability
- Pricing

But the user still has to interpret all of these signals and answer:

> **"Which astrologer is actually right for my problem?"**

This creates a selection problem.

### Current journey

`Browse → Filter → Compare → Choose → Explain the problem`

### Proposed journey

`Question → Context → Match → Understand why → Consult`

The product opportunity is to move from **expert discovery** to **intent-led matching**.

---

# 💡 The Product Thesis

### The best astrologer is not necessarily the highest-rated astrologer.

The right expert depends on the:

**Question + Tradition + Language + Availability + Context**

So AstroLive Match focuses on finding the **best available expert for the user's specific question**, rather than presenting a generic list of astrolo

# 🧩 What I Built

## AstroLive Match

A question-first matching layer designed to work with the existing AstroLive marketplace.

#CONCEPT#
                    USER INTENT
                        │
                        ▼
              ┌───────────────────┐
              │ Candidate Experts  │
              └───────────────────┘
                        │
       ┌────────────────┼────────────────┐
       ▼                ▼                ▼
  Topic Fit       Tradition Fit     Language Fit
       │                │                │
       └────────────────┼────────────────┘
                        ▼
                  Availability
                        │
                        ▼
                Quality Signals
                        │
                        ▼
              Controlled Exploration
                        │
                        ▼
                 Ranked Matches

#FLOW#

01
Question
   ↓
02
Context
   ↓
03
Astrologer Match
   ↓
04
Why this match?
   ↓
05
Availability fallback
   ↓
06
Consultation brief
   ↓
07
Decision Confidence
