# Barking with Style Dog Grooming — Grimsby

Research notes for this prospect, run 2026-09-07.

## History check

`prospects/` and `prospects/DONE.md` did not exist before this run — this repository
had no commits and the GitHub remote was confirmed empty via the API (`409 Git
Repository is empty`). This is the first-ever run of the pipeline, so there was no
prior prospect list or prior notes.md files to review, and no visual metaphor /
palette to consciously differ from. The design decisions below were made purely
on what fit this business, not as a reaction to a previous run.

## The business

- **Name:** Barking with Style Dog Grooming
- **Owner:** Becky (Wesley)
- **Address:** 166 Castle St, Grimsby, DN32 7LA
- **Phone:** 07786 428940
- **Hours:** Mon–Fri, 9am–5pm
- **Model:** 1-to-1 salon-based groomer — one dog booked into the salon at a time,
  not a multi-table/multi-dog salon
- **Breed range:** explicitly "teacup to giant", all breeds
- **Specialisation called out in her own listings:** takes on nervous, reactive
  and "difficult to groom" dogs
- Fully qualified & insured (stated across listings)
- Facebook: 100% recommend rating from 23 reviews. Instagram (@barkingwithstyle)
  and a TikTok presence also exist.

## Confidence on "no website"

Medium-high. Targeted searches for the business name plus "website", plus
guesses at likely domains (barkingwithstyledoggrooming.co.uk,
barkingwithstyle.co.uk), turned up nothing beyond Facebook, Instagram, and
third-party directory/aggregator listings (TheBestPlaces.uk, Pata, MyPetGroomer,
Yell, Bark.com). No independent site was found in any search. Absence of
evidence isn't proof, but this was checked specifically and repeatedly, not
just assumed from a single query.

## Access limitation this run

WebFetch was blocked by the sandbox's network egress policy for every
non-search domain I tried, including Facebook, directory sites, and (for Step
3) ordinary competitor business websites and design-inspiration articles like
colorlib.com and designerpawssalon.com — even Wikipedia returned
`EGRESS_BLOCKED`. So I could not read individual review text directly. All
research came from WebSearch's synthesised summaries of Facebook/directory
listing pages, which repeatedly and consistently surfaced the same facts
(100%/23 reviews, the 1-to-1 model, "teacup to giant", "nervous, reactive and
difficult to groom dogs" as her own stated specialisation). The trust-section
copy on the site is explicitly labelled as paraphrased sentiment inferred from
that aggregate signal and her own positioning, not lifted quotes — I did not
fabricate named testimonials or invent specific review text I couldn't verify.

## The essence (Step 2)

This is not "a dog groomer" — the category label undersells what's actually
distinctive. The defining fact is structural: Becky only has one dog in the
salon at a time. That's a deliberate, slower-to-run business model choice, and
it's paired with an explicit specialisation in dogs that struggle at other
groomers (nervous, reactive, previously difficult). Put together, the essence
is: **a calm, unhurried, one-to-one environment built specifically for dogs
who don't do well in a typical multi-dog salon.** The 100%-recommend/23-review
signal reinforces that this isn't just a claim, it's apparently working. The
personality that comes through is patient and unrushed rather than glossy or
"pampering-spa" — this reads as a practical, trust-building service, not a
luxury indulgence.

## Category inspiration (Step 3)

WebFetch being blocked meant I couldn't browse individual competitor sites
directly, so I used WebSearch's synthesis of curated "best dog grooming
websites" roundups (Colorlib's list, Designer Paws Salon, Snobby Dogs, Floof,
Kibble) to understand genre conventions:

- Pastel pink or baby-blue palettes are extremely common, often with rounded
  playful fonts and paw-print iconography used decoratively and repeatedly.
- Luxury-spa aesthetics (gold/beige "pampering" language) are common at the
  premium end.
- Before/after galleries and real photos of groomed dogs are standard trust
  devices.
- Credentials and competition awards are frequently foregrounded for
  authority.

**Kept:** a genuine trust/social-proof section, a clear services structure,
a real closing CTA with the phone number, credentials mentioned once (not as
badges plastered everywhere).

**Deliberately broken:** no pastel pink/blue palette (too generic-cute for what
is fundamentally a calm/patience-based service, not a pampering one), no
luxury-spa gold/beige framing (this isn't about indulgence, it's about
practical trust), no paw-print icon spammed across every section (used once,
purposefully, on the one relevant service card), no before/after gallery (no
real photography exists for this mock-up, and it would misrepresent actual
work) — replaced with a narrative device that shows the *emotional* before/after
of the dog instead of a coat/cut before/after.

## Design decisions

- **Accent colour:** deep sage green (`#4e6b52`), chosen because it reads as
  calm and grounded rather than "vet-clinic blue" or "cutesy pastel pink"
  groomer branding, and avoids both the beige+brass "artisan" cliché and
  AI-purple. A muted rust/amber (`#c1622d`) is used only as a *narrative*
  colour inside the centrepiece animation, to represent the "tense" state
  before it resolves into the sage "calm" state — it's not a competing brand
  colour, it's part of the story.
- **Type pairing:** Fraunces (a warm, slightly characterful serif with real
  personality) for headings, Work Sans for body copy. Deliberately not Inter.
- **Spacing/radius system:** an 8px-based spacing scale (`--space-1`
  through `--space-8`) and a three-step corner-radius system (6px small
  elements, 16px cards, 32px large hero/CTA shapes) used consistently
  throughout rather than arbitrary per-component values.

## The centrepiece (Step 4's "genuinely inventive moment")

**"The Calm Line"** — a pinned, scroll-scrubbed section built with GSAP +
ScrollTrigger. A hand-drawn heartbeat/pulse line runs across the top: at the
start of the scroll it's fast, tall, jagged, and rust-coloured (visually
"anxious"); as the visitor scrolls, the amplitude shrinks, the frequency
slows, the jaggedness smooths into a clean sine wave, and the colour
interpolates from rust to sage in real time (computed per-frame from scroll
progress, not a canned loop). Underneath, an inline SVG dog reacts in sync:
ears pinned back rotate into a relaxed position, small "tension tick" marks
near the shoulder fade out, the head lifts as if looking up, the mouth curve
widens into a relaxed pant, a soft glow appears behind the dog, and the tail
loosens from tucked into a gentle wag. Four short captions crossfade in time
with the scroll ("A lot of dogs arrive braced..." through "...that's usually
when the actual groom begins").

This is a literal visualisation of the actual business model (a nervous dog
settling over the course of an unhurried appointment), not a generic "reveal
on scroll" trick or an object travelling along a path — the metaphor is a
physiological one (a pulse literally calming down), which is different in
kind from a journey/travel metaphor and specific to what makes this groomer
different from a standard one.

## A build bug worth flagging for future runs

Two real GSAP/CSS interaction bugs turned up during testing and are fixed in
the shipped file, worth remembering for future prospects that use a similar
pinned ScrollTrigger section:

1. `overflow-x: hidden` on `<body>` silently breaks native CSS
   `position: sticky` in some browsers (it changes what a sticky element is
   "sticky" relative to). The site originally used CSS sticky positioning for
   the pinned dog illustration and it broke completely once `overflow-x:
   hidden` was added to prevent horizontal scroll. Fixed by using GSAP
   ScrollTrigger's own `pin` option instead of CSS `position: sticky`.
2. `html { scroll-behavior: smooth }` conflicts with ScrollTrigger's
   scrub-based scroll-linked animation and was removed.

Both were caught by actually loading the page in a headless browser and
scrolling through it programmatically, not just by reading the code, which is
why it's worth doing that check on future builds too.

## Honest caveats for Ben to sanity-check

- I could not read individual Facebook review text (network access to
  Facebook was blocked in this environment), so the "What people notice"
  trust section is paraphrased from the aggregate 100%/23 signal and Becky's
  own stated specialisation, not quoted from real customers. It's labelled as
  paraphrased on the page itself, but worth a skim before sending.
- I could not verify current pricing, so the site deliberately avoids listing
  prices and says they're confirmed by phone.
- Business hours, address, and phone number were consistent across every
  source I found (Facebook, TheBestPlaces.uk, Pata), but I'd still suggest a
  quick glance/call before this goes out, standard due diligence for any
  scraped contact detail.
