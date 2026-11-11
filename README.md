# ScamShield — Spot the scam before it spots you

A single-file web app that helps everyday Indians spot fraud before it costs them money.

## What it does

- **Message Lab (Analyzer)** — Paste any suspicious SMS, WhatsApp message or email. ScamShield checks it against 18 fraud-signal rules (60+ patterns: OTP/PIN/CVV requests, fake police or "digital arrest" claims, KYC-block threats, shortened links, false urgency, prize promises, UPI collect traps, remote-access requests…) and stamps a verdict: **SCAM / SUSPICIOUS / LOOKS SAFE**, with a risk meter, the exact red flags found, the phrases highlighted in your message, plain-language reasons, and what to do next. Try the four one-tap sample messages (KYC block, digital arrest, job offer, genuine).
- **The Scam Files** — The 8 scam playbooks running in India right now: Digital Arrest, KYC/Account Block, Parcel & Customs Fee, Job Offer Fee, UPI Refund/Collect, Lottery & Prize, Investment/Trading Tips, Fake Loan App. Each file shows how the script goes, the red flags, what they actually want, and the safe reply.
- **Spot-the-Scam quiz** — 8 real-style messages; you decide scam or safe, with the tell explained after every round, a final score and verdict.
- **If it already happened** — A first-hour action plan and the one number to remember: **1930**, India's National Cybercrime Helpline (free, 24×7), plus links to cybercrime.gov.in, RBI and NPCI.
- **Daily Habits** — 6 habits that make you a hard target, with a progress ring. Saved on your device.

## How it works

- One self-contained `index.html` — no backend, no signup, no tracking.
- Everything is stored in `localStorage` only: messages checked, quiz best score, habits.
- Cinematic intro (tap to skip; quick version on return visits) and a 3-step onboarding coach on first visit.
- Warm editorial design (ivory paper, espresso ink, bronze/amber/terracotta), Fraunces + Inter, Ken Burns photography.
- Works offline once loaded, except for the photos and fonts.

## Disclaimer

ScamShield gives guidance based on common fraud patterns — it is not a guarantee. A message can look safe and still be a scam. When in doubt: don't click, don't pay, and call **1930** or your bank on a number you already trust.

## Run it

Open `index.html` in any browser, or visit the GitHub Pages link for this repo.
