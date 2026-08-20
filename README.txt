ASTROLIVE MATCH — UPDATED MINIMAL PROTOTYPE

Design: minimal Google-like UI, white/grey, restrained blue accent.

Functional MVP:
1. Question-first topic selection + free-text intent hint
2. Tradition + language context
3. Weighted, explainable matching
4. Cold-start exploration for a new verified astrologer
5. Availability-aware fallback
6. Consultation brief
7. Decision Confidence before/after
8. Inspectable ranking model

Business logic added:
- User-fit ranking does not use price/margin as a primary user signal.
- New verified astrologers receive a limited exploration bonus.
- Supply-side exposure and margin are treated as marketplace guardrails, not reasons to route users to a worse expert.

All data are mock/demo. No real calls, payments, or astrology calculations.
