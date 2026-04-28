# Prompt 2: Inquiry-to-Booking Conversion System

## Purpose
Generate the full sales sequence from first inquiry to signed contract — inquiry response, post-tour follow-up, proposal copy, objection handlers, and deposit confirmation.

## When to Use
- Setting up an automated CRM sequence (HoneyBook, Dubsado, 17hats)
- Training a new venue sales coordinator
- Overhauling a low-converting inquiry pipeline
- Recovering prospects who went cold after a tour

---

## The Prompt

```
You are an expert wedding venue sales copywriter. Generate a complete Inquiry-to-Booking Conversion System.

Venue: [venue_name] | [city_state]
Style: [style_keywords]
Capacity: [capacity_range]
Services: [services_included]
Price: [price_range]
Packages: [special_packages]
Coordinator: [coordinator_name]

DELIVER ALL OF THE FOLLOWING:

**1. INQUIRY RESPONSE EMAIL (200 words)**
- Subject line that acknowledges their date
- Warm, personal tone (not corporate)
- 3 bullets: what makes the venue right for them (based on style_keywords)
- Clear next step: tour invitation with 2-3 date options placeholder
- Signature block with coordinator name + direct line placeholder

**2. POST-TOUR FOLLOW-UP SEQUENCE (3 emails)**
Email 1 — Same-day thank you (150 words): Recap 3 things couple loved, answer any questions from tour, soft urgency (date availability)
Email 2 — Day 3 nurture (200 words): Real wedding story or venue feature spotlight, social proof angle, "I wanted you to see this" feel
Email 3 — Day 7 decision-support (200 words): Address the #1 objection (price vs. value), what's included breakdown, what they lose by waiting (date hold policy)

**3. PROPOSAL / QUOTE COVER LETTER (250 words)**
- Custom to couple's style and vision
- Package options presented as experiences, not line items
- Payment timeline presented positively ("flexible milestone payments")
- Clear date hold policy (X days to sign — use [DAYS] placeholder)
- Warm closing + coordinator direct contact

**4. OBJECTION HANDLER SCRIPTS (5 scenarios, word-for-word)**
A. "We're still looking at other venues" — reframe comparison, anchor on unique features
B. "Your price is higher than [Competitor]" — value bridge, cost-per-guest math, what's included
C. "We need to think about it / talk to family" — timeline urgency, date scarcity, easy next step
D. "We wanted outdoor only / indoor only" — flexibility reframe, weather contingency plan
E. "It's farther than we wanted" — destination experience reframe, guest hotel partnerships, shuttle angle

For each: opening acknowledgment (1 sentence) → pivot (2 sentences) → close (1 sentence)

**5. DATE HOLD / DEPOSIT CONFIRMATION EMAIL (150 words)**
- Warm congratulatory tone
- Confirm date, package, next steps
- Payment link placeholder + contract DocuSign placeholder
- Set expectations for planning timeline

COMPLIANCE:
- Force majeure: do NOT promise weather guarantees; include "subject to venue's weather contingency policy" where applicable
- FTC: all "typical couples" or "most couples find" language must be framed as experience-based guidance, not guarantee
- ADA: if venue has specific accessible entrances, note "accessible entrance available — ask your coordinator for details"
- Nevada NRS 122: wedding ceremony requirements are couple's responsibility; venue is not the officiant
- TCPA: if follow-up includes SMS option, include opt-out instruction
```

---

## Example Input

```
Venue: Desert Rose Estate | Henderson, NV
Style: Desert-chic, romantic, modern rustic
Capacity: 50–300 guests
Services: In-house catering, full open bar (Nevada Catering Liquor Permit #NV-CLP-20241184), bridal suite, day-of coordinator, 14 vendor-preferred list
Price: Packages from $8,500; Grand Affair from $14,000
Packages: Elopement ($2,500), Micro-Wedding ($5,500), Grand Affair (from $14,000)
Coordinator: Priya Vasquez, CWEP
```

---

## Tips

- Load the inquiry response into HoneyBook/Dubsado as a "new inquiry" workflow template — triggers within 30 minutes of submission
- The Day 3 email is the highest-converting in the sequence; customize the "real wedding spotlight" section with an actual past event
- For the objection scripts, role-play these with your coordinator before going live — delivery matters as much as the words
- The deposit confirmation email should be sent within 1 hour of receiving the signed retainer
