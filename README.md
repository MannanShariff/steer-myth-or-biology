# Myth or Biology: a playable myth-or-fact quiz (Steer Hackathon, PS1)

**Open:** `index.html` in any phone browser. Single file, no login, no build step. Live copy (GitHub Pages, if enabled): see repo Settings > Pages.

**Target device/browser:** mobile first (about 400px wide), tested logic in Node; designed for current Chrome, Safari and Edge. English and Hinglish toggle.
**Completion status:** playable end to end (hook, 6 rounds, personal readout, share, handoff). Layout not yet tested on a physical phone. The lead form only saves inside claude.ai; standalone it falls back to "copy my summary".

**Trigger (first 3 seconds):** an animated clock sweeps to 4pm and asks "Willpower, or biology?" The first tap is what is in your hand at 4pm.
**Value:** six myth-or-fact rounds (swipe cards, a guess-the-number slider, an optional private waist/BMI check against Asian Indian flags), each with a plain answer and source links, ending in a personal "metabolic wrapped" card built around the user's biggest doubt, with questions to ask a doctor.
**Next step:** "Talk to a Steer doctor" with a consent-based lead form showing what the care team would see, plus "Challenge a friend" on WhatsApp.

## Sources (every claim on the page)
- Wilding et al., Diabetes Obes Metab 2022, STEP 1 trial extension: https://pmc.ncbi.nlm.nih.gov/articles/9542252
- Moiz et al., Annals of Internal Medicine 2025: https://pubmed.ncbi.nlm.nih.gov/39761578/
- Obesity and Dyslipidemia in South Asians, Nutrients 2013: https://pmc.ncbi.nlm.nih.gov/articles/PMC3738996
- ENDO 2021 STEP 1 DEXA substudy (Patient Care): https://www.patientcareonline.com/view/semaglutide-2-4-mg-reduces-visceral-adiposity-improves-lean-body-mass-to-fat-mass-ratio
- Tolerability of nausea and vomiting, PMC4010971: https://pmc.ncbi.nlm.nih.gov/articles/PMC4010971
- 2 Minute Medicine summary of the 2025 Annals review: https://2minutemedicine.com/glucagon-like-peptide-1-receptor-agonists-and-co-agonists-safe-and-effective-for-weight-loss

No drug is named or promoted, no weight-loss promises, no before/after bodies. Educational only, not medical advice.

## Contributors and tools
Solo. Built with Claude (Anthropic) for research, copy and code. Fonts: Instrument Serif, DM Sans, Caveat (Google Fonts). No other external assets.
