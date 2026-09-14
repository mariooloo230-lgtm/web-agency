# Well Swept Chimney Sweep — Bexhill-on-Sea

Research notes for this prospect, run 2026-09-14.

## History check

`prospects/DONE.md` lists one prior prospect: Barking with Style Dog Grooming
(Grimsby, 2026-09-07), a one-to-one dog groomer whose centrepiece was "The
Calm Line", a scroll-scrubbed heartbeat/pulse line that smoothed and shifted
colour from rust to sage as an illustrated dog relaxed. Accent colour was
deep sage green (#4e6b52), type pairing was Fraunces + Work Sans, spacing was
an 8px grid with a 6/16/32 radius system.

This run deliberately differs: different trade (chimney sweep, not another
pet-care business), a different kind of centrepiece mechanic (a masked
reveal/transformation within one fixed illustration, not a path/line that
smooths over a continuous interpolation), a different accent colour (ember
red-orange, not green), and a different type pairing (Bricolage Grotesque +
Karla, not Fraunces + Work Sans). See "Difference from prior runs" below for
the full comparison.

## The business

- **Name:** Well Swept Chimney Sweep
- **Owner:** Laura
- **Location:** Bexhill-on-Sea, East Sussex (no public street address found,
  consistent with a mobile trade that visits customers rather than trading
  from fixed premises)
- **Area covered:** Bexhill, Hooe, Crowhurst, Hastings, and surrounding areas
- **Phone:** 07810 111732
- **Email:** WellSwept@outlook.com (appears consistently across Facebook and
  directory listings as the business contact address)
- **Facebook:** 100% recommend rating from 47 reviews
- **Certifications:** Member of the Guild of Master Chimney Sweeps. Fully
  insured, certificates provided.
- Services confirmed via search: chimney sweeping, CCTV flue inspection,
  bird's nest removal, bird guard fitting, carbon monoxide alarm advice, an
  online booking system (hosted on a third-party platform, The Stove Guys,
  not her own site)

## Confidence on "no website"

Medium-high. Repeated targeted searches for "Well Swept Chimney Sweep"
Bexhill plus "website" surfaced only Facebook, Nextdoor, and third-party
directory/booking listings (The Stove Guys, Ratings Plus, Thomson Local,
Checkatrade's category page, local-quotes.co.uk). No independent domain for
this specific business turned up in any search.

One important caveat I checked carefully: there are two other, entirely
unrelated companies with very similar names that do have their own websites:
"WellSwept Chimneys" (wellsweptchimneys.com) is based in Victoria Harbour,
Ontario, Canada, serving North Simcoe and Muskoka, confirmed via search to be
a different company on a different continent. "wellswept.org.uk" is a
different chimney sweep in Norfolk (NR29 4QT), HETAS-approved, also
unrelated to Laura's Bexhill business. I did not attribute either of those
companies' facts (including the Norfolk one's HETAS approval) to Laura. All
facts in this notes file and on the site are specific to search results tied
to Laura, Bexhill-on-Sea, and the 07810 111732 / WellSwept@outlook.com
contact details.

## Access limitation this run

Same limitation as the previous run: WebFetch returned `EGRESS_BLOCKED` for
every non-search domain attempted, including Facebook, Nextdoor, directory
sites, and ordinary competitor/inspiration websites for Step 3 (tomsweep.co.uk,
smithschimneysweeping.co.uk, wellsweptchimneys.com, ratingsplus.co.uk, even
Wikipedia). All research came from WebSearch's synthesised summaries, which
repeatedly and consistently surfaced the same facts (47 reviews, 100%
recommend, the area list, the Guild membership, the "clean and tidy" /
"friendly and informative" sentiment). No individual review text was quoted
verbatim; the trust section on the site paraphrases the aggregate sentiment
and says so explicitly.

## The essence (Step 2)

The category label "chimney sweep" undersells this. Two things make Laura's
business distinctive, and they reinforce each other:

1. **She's a woman in a trade that's still overwhelmingly male.** Search
   summaries describing her business explicitly frame this as notable
   ("breaking into a field where few women had ventured", "progress knows no
   gender boundaries"). It's a genuine, specific fact about this business,
   not a generic trait every sweep could claim.
2. **What her reviews actually praise isn't the sweep itself, it's the
   cleanliness and communication around it.** The recurring words are "clean
   and tidy", "quick, friendly and informative". That's notable because
   chimney sweeping is culturally associated with mess and soot. The
   contrast, an inherently dirty job done with visible precision and left
   spotless, is the emotional hook, more than "she sweeps chimneys well."

Put together: **a trade that looks like it should be dirty and rough, done
by someone who treats it as a precision job and leaves nothing behind.**
That tension (soot and grime as the raw material of the job vs. the
immaculate, reassuring result) drove every design decision below.

## Category inspiration (Step 3)

WebFetch being blocked meant I relied on WebSearch's synthesis of roundup
articles about chimney sweep company websites (CyberOptik's "Best Chimney
Sweep Websites", ServiceTitan's equivalent, Freshy's chimney repair roundup)
rather than browsing live competitor sites directly.

Recurring conventions in the category:
- Hero sections pairing a safety message with an obvious booking CTA
- Every service (sweep, inspection, liner, cap) treated as its own
  dedicated block, often with badges for certifying bodies (Chimney Safety
  Institute of America equivalent) and licensing/insurance
- Before/after photography of the flue or the technician at work
- Dark-background hero sections with bold, sometimes clashing colour (one
  cited example used purple and orange together)
- Trust badges and Google Reviews widgets stacked densely near the top

**Kept:** a clear hero + phone CTA, a real services breakdown, a genuine
trust/credentials section (Guild membership, insured, 100%/47 reviews), a
closing CTA with the real phone number, a footer with area covered.

**Deliberately broken:** no stock "technician in hi-vis smiling at camera"
photography (none exists for this mock-up, and it would misrepresent her
actual work), no dense wall of trust badges, no before/after photo gallery
(replaced with an illustrated before/after of the flue itself, which is more
honest than implying we have real job photos), no bold clashing colour
scheme, just one accent colour used consistently, and no generic "Our
Services" grid of three identical icon cards, the services are a single
list of five items with progressively larger visual weight for the two most
important ones (the sweep itself, and the certificate), not implying equal
weight or count symmetry.

## Design decisions

- **Accent colour:** an ember red-orange (`#c23c1f`), chosen because it
  reads as warmth and fire (what a working chimney is actually for) without
  being the beige+brass "artisan" cliché or AI-purple, and is a different
  hue family entirely from the previous run's sage green so the two mock-ups
  don't read as the same template with a colour swapped.
- **Type pairing:** Bricolage Grotesque (a characterful grotesque sans with
  irregular, slightly hand-cut letterforms) for headings, Karla for body
  copy. Neither font was used in the previous run (which paired a serif,
  Fraunces, with Work Sans), and neither is Inter.
- **Spacing/radius system:** an 8px spacing scale (`--space-1` through
  `--space-8`), and a three-step radius system (8px small elements, 20px
  cards, 40px large shapes), a different set of concrete values from the
  previous run's 6/16/32 so it isn't a copy-pasted system, though the
  underlying "consistent scale" method is the same good practice.

## The centrepiece (Step 4's "genuinely inventive moment")

**"The Clean Flue."** A pinned, scroll-scrubbed cross-section illustration of
a chimney, from pot to hearth, built with GSAP + ScrollTrigger. This is
deliberately a different *kind* of moment from the previous run's centrepiece
(a continuous physiological interpolation of a pulse line) and is not a
travel/journey metaphor (nothing moves along a path across the viewport).
Instead it's a masked reveal within one fixed illustration:

- The flue starts fully covered in a soot texture (dark, mottled, grimy).
- As the visitor scrolls, an SVG clip-path shrinks from the top down,
  revealing clean warm brick underneath, starting at the hearth and working
  upward. This isn't arbitrary: real chimney sweeps work rods and brush up
  from the fireplace to the chimney pot, so the "clean" appears from the
  bottom of the flue first, exactly matching how the job is actually done.
- At the same time, a soot pile grows at the hearth (soot dislodged from the
  walls has to go somewhere, it falls down and collects), then shrinks back
  to nothing near the end of the scroll (it gets bagged up and taken away).
- Small soot flecks near the boundary fade out in sequence as the clean edge
  passes them, for texture.
- In the final beat, a warm ember glow blooms at the hearth (the fire that
  can now safely be lit) and a small certificate/tick badge fades in
  (the paperwork that proves it's done).
- Three short captions (numbered 01/02/03, "before", "the sweep", "after")
  cross-fade in sync with the three phases.

The whole thing is one continuous GSAP timeline scrubbed to scroll position,
built from real SVG shapes and clip-paths, not a video or Lottie file.

## Mobile and reduced-motion handling

- `prefers-reduced-motion` is checked on load. If set, all `.reveal`
  elements are shown immediately, the centrepiece's scroll spacer height is
  collapsed (so it doesn't leave a large empty gap), and the illustration is
  set straight to its finished state (clean flue, ember glow, certificate
  badge, final caption) rather than attempting any animation.
- On viewports under 760px, `gsap.matchMedia` swaps the centrepiece from a
  pinned (`ScrollTrigger` `pin: true`) section to an unpinned one, so the
  scrub animation still plays as the visitor scrolls past it, but nothing
  hijacks or locks touch scrolling on mobile.

## Testing

I could not load the real GSAP/ScrollTrigger CDN files in this sandbox
(cdnjs.cloudflare.com is blocked by the environment's egress policy for
both `curl` and headless-browser traffic, not just WebFetch), so I could not
watch the real scroll animation play in a browser. To still catch real bugs
before shipping, I:

- Rendered the page with Playwright/Chromium using `prefers-reduced-motion:
  reduce` emulated (a real, unstubbed code path) and screenshotted it at
  1300px and 390px wide, scrolled through the whole page. This caught two
  real bugs, fixed before shipping:
  1. The centrepiece's scroll-spacer (`340vh`, needed for the desktop pin)
     was left at full height in the reduced-motion path, leaving a huge
     blank gap where the pinned section should have been. Fixed by
     collapsing it to `auto` height whenever reduced motion is detected.
  2. The first version of the "About Laura" illustration was an abstract
     blob that didn't read as anything. Redrawn as a clearer, simpler
     composition: a silhouette bust holding a rod that connects to a
     chimney pot with a brush tuft just pulled clear of it.
- Wrote a small local stub of the `gsap`/`ScrollTrigger` API (just enough of
  `.set`, `.timeline().to()`, `.fromTo()`, `.utils.toArray`, `.matchMedia`)
  and served the real page through it via Playwright request interception,
  to confirm the actual (non-reduced-motion) script runs without throwing
  and that every element ID and selector it references genuinely exists in
  the DOM. This isn't a substitute for watching the real animation, but it
  does rule out the class of bug that would break the page outright (typos
  in IDs, calling GSAP with malformed arguments).
- Confirmed no horizontal scroll/overflow at both 1300px and 390px widths in
  both the stubbed and reduced-motion runs.

Ben, it's worth a real once-over of the live scroll animation in an actual
browser before this goes out, given I couldn't watch it play myself in this
environment.

## Honest caveats for Ben to sanity-check

- I could not read individual Facebook review text directly (network access
  blocked), so "What people notice" paraphrases the aggregate 100%/47
  signal and the recurring themes WebSearch surfaced ("clean and tidy",
  "friendly and informative"), it isn't quoting anyone.
- The email address (WellSwept@outlook.com) is her own listed business
  contact, pulled from public listings, not one I invented, but it's still
  worth a quick glance/call before sending anything, standard due diligence
  for scraped contact details.
- No pricing is shown anywhere on the site, deliberately, since I couldn't
  verify current rates.
- I genuinely could not watch the scroll animation render in a real browser
  in this environment (see Testing above), please open it and scroll through
  once yourself before sending.
