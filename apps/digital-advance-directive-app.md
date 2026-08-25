# Privacy Policy — Digital advance directive app

# Bridges AI Enterprises — Privacy Policy (Portfolio-Wide)

**Effective date:** [FILL IN ON PUBLISH]
**Applies to:** All apps published by Bridges AI Enterprises ("BAE," "we,"
"us"), unless a specific app links to a more specific addendum below, in
which case both this document and that addendum apply together.

*This is a starting-point draft based on BAE's actual technical
architecture (see `docs/PRIVACY_NOTES.md`). It is not a substitute for
review by a licensed attorney, particularly for apps handling health,
financial, biometric, or age-restricted content — see the per-category
addenda for those.*

## 1. Who we are

Bridges AI Enterprises is a single-owner software portfolio. Every app in
this portfolio shares common backend infrastructure (the "BAE AI Gateway")
for AI features, so this policy is written once and applies across apps,
with app-specific detail layered on top where an app's data is meaningfully
different from the norm.

## 2. What we collect

**Account/identity data:** whatever the individual app requires to function
(e.g., email for login) — collected by that app, not by us on its behalf
except where noted.

**Usage and prompt data:** if the app includes AI features, your inputs
(chat messages, generation prompts) pass through our shared AI Gateway.
These are encrypted at rest. We do not run content moderation or scrub
personal information from what you type before storing it — avoid entering
information you don't want retained if you're unsure.

**Payment data:** if the app has paid features, payment is processed by
Stripe. We store a card fingerprint (not your card number) and a Stripe
customer ID, used only to detect the same card being used to abuse free
trial credits across multiple accounts.

**Device/technical data:** standard technical logs (timestamps, error
data) for reliability and abuse prevention.

## 3. How we use it

- To provide the app's core functionality
- To operate AI features (routing your input to a language model and
  returning the result)
- To prevent fraud and abuse of free-credit systems
- We do not sell personal data to third parties
- We do not use your data to train AI models

## 4. Who we share it with

- **AI model providers** (e.g., Anthropic), to generate a response to your
  input — sent per-request, not stored by the provider beyond their own
  standard retention policy
- **Stripe**, for payment processing, if the app has paid features
- **Media generation providers** (e.g., fal.ai, ElevenLabs), only for apps
  with image/video/voice generation features
- We do not share data with data brokers or advertisers

## 5. Your rights

You can request:
- **Access** to what data we hold associated with your account
- **Deletion** of your account and associated data

To make either request, contact: [FILL IN SUPPORT EMAIL]

Note: some data (e.g., anonymized usage logs not linked to an account
identifier) may not be deletable on an individual basis because it isn't
stored in an individually-identifiable way.

## 6. Data retention

Data is retained as long as your account is active, plus a reasonable
period afterward for fraud prevention and legal compliance, unless you
request earlier deletion.

## 7. Children's privacy

Our apps are not directed at children under 13, and we do not knowingly
collect data from children under 13. If a specific app is intended for a
younger audience, that app's own policy addendum will say so explicitly
and describe additional safeguards.

## 8. Changes to this policy

We may update this policy as apps or infrastructure change. Material
changes will update the effective date above.

## 9. Contact

Bridges AI Enterprises
[FILL IN SUPPORT EMAIL]


---

## Addendum: Health-Related Apps

*Applies in addition to the Master Privacy Policy for apps that store or
display medical, medication, diagnosis, or end-of-life information.*

**What's different about this data:** this app may store information
about medical conditions, medications, allergies, diagnoses, advance
directives, or emergency contacts. This is more sensitive than typical
app data, and some of it may be shared with people you designate
(caregivers, emergency responders) at your direction.

**Important — not a covered entity:** Bridges AI Enterprises is not a
healthcare provider, health plan, or healthcare clearinghouse, and this
app is not a substitute for professional medical advice, diagnosis, or
treatment. HIPAA generally does not apply to data you enter directly into
a consumer app like this one, unless the app is used by or on behalf of a
covered healthcare provider — this app is not. Consult a lawyer if this
app will be used in a clinical or provider context.

**Caregiver/shared access:** if this app supports sharing your
information with a caregiver, family member, or via QR code/link, you
control who receives that access, and are responsible for who you share
it with. Revoking access should stop future viewing but does not retract
what's already been viewed or saved by someone you shared with.

**Emergency-facing data:** if this app displays a subset of your data
without login (e.g., for first responders), that data is, by design,
accessible to anyone who scans the code or link — don't include more
than you're comfortable being publicly viewable in an emergency.

**Deletion:** deleting your account deletes this health information from
our systems, but does not retract copies already shared with or saved by
a caregiver.
