# Hair, There & Everywhere — Haddington, East Lothian

Research notes for this prospect, run 2026-09-21.

## History check

`prospects/DONE.md` lists two prior prospects:

1. Barking with Style Dog Grooming (Grimsby, 2026-09-07) — a one-to-one dog
   groomer. Centrepiece was "The Calm Line", a scroll-scrubbed heartbeat/pulse
   line that continuously interpolated from jagged rust to smooth sage as an
   illustrated dog relaxed. Accent: deep sage green (#4e6b52). Type: Fraunces
   + Work Sans. Radius steps: 6/16/32.
2. Well Swept Chimney Sweep (Bexhill-on-Sea, 2026-09-14) — a chimney sweep.
   Centrepiece was "The Clean Flue", a masked reveal within one fixed
   cross-section illustration (a soot clip-path shrinking away from the
   hearth upward). Accent: ember red-orange (#c23c1f). Type: Bricolage
   Grotesque + Karla. Radius steps: 8/20/40.

Both centrepieces are, mechanically, a single continuous element (a line, or
a masked area) transforming smoothly along the scroll. This run deliberately
uses a different *kind* of mechanic: **an assembly of several independent
discrete objects, each entering a static scene on its own path and settling
into place in sequence**, not one shape smoothly interpolating or a mask
sliding over one fixed illustration. See "The centrepiece" below. It's also a
different trade (mobile hairdresser, not pet care or a chimney trade), a
different accent hue family (wine/burgundy, not green or orange-red), a
different type pairing (Frank Ruhl Libre + Manrope, neither used before, and
not Inter), and a different concrete spacing/radius scale (10/24/48, radius
steps 10/24/48, spacing steps 8/16/24/32/48/72/104/160).

## The business

- **Name:** Hair, There & Everywhere (also seen without the comma as "Hair
  There & Everywhere" on some directory listings; Facebook's own page name
  uses the comma, which is what the site uses).
- **Owner:** Michele Hunter.
- **Location:** Haddington, East Lothian, Scotland. Mobile only, no fixed
  salon premises — she travels to clients' homes in and around East Lothian.
- **Phone:** 07790 662450.
- **Email:** michelehunter@hotmail.com (her own listed business contact,
  appearing consistently across search results, not invented).
- **Experience:** approximately 20 years hairdressing in total, the last 13
  years specifically as a mobile/home-visit service.
- **Facebook:** 100% recommend rating from 25 reviews.
- Also has a third-party Setmore booking page
  (hairthereandeverywhere.setmore.com), the same kind of third-party booking
  tool Well Swept used (The Stove Guys) rather than an owned website.

## Confidence on "no website"

Medium-high. Repeated targeted searches for the business name plus
"website", plus checks against the Setmore booking link and several
directory/listing sites (beautynailhairsalons.com, Thomson Local,
findglocal.com, internetbusinessdirectory.co.uk, East Lothian Courier's
directory), turned up no independent domain for this business. Her only
presence beyond Facebook is that third-party booking page and directory
listings.

One thing checked carefully: "Hair There and Everywhere" is a common enough
name that several *entirely unrelated* businesses share it — one in East
Kilbride, one in Chester-le-Street, one on the Wirral (per a Dun & Bradstreet
listing), and an Australian one ("Hair there & everywhere by Kylee" in
Tahmoor, NSW). None of those were used as a source for any fact here. Every
fact in this file and on the site is tied specifically to the Haddington,
East Lothian listing, Michele Hunter's name, and the 07790 662450 phone
number, which appeared together and consistently across multiple
independent sources (search snippets naming both the phone number and
Michele Hunter for the same Haddington listing).

## Access limitation this run

Same limitation as both previous runs: WebFetch returned `EGRESS_BLOCKED` for
every non-search domain attempted this run too, including Facebook,
directory sites, Wikipedia, and (for Step 3) live competitor/inspiration
hair-salon websites. All research came from WebSearch's synthesised
summaries. No individual review text was quoted verbatim anywhere; the
trust section on the site paraphrases the recurring themes WebSearch
surfaced (100%/25 recommend, "a lovely lady", "always great haircut and
colour", "look forward to being there", "professional and knowledgeable",
"extremely impressed"), and says explicitly that it's paraphrased, not
quoted.

## The essence (Step 2)

"Mobile hairdresser" undersells this. The specific, distinctive fact is
*why* Michele went mobile, which search summaries describe consistently:
she made the deliberate choice to start travelling to clients specifically
**to reach people who find it hard to get out** (mobility issues, no easy
transport, a rural East Lothian address) **and to keep it more affordable**
than a shop appointment. That's not a generic convenience pitch, it's an
accessibility-and-cost decision that shaped the whole business model, and
she's stuck with it for 13 years.

Layered on top of that: the reviews don't read like people grading a
transaction. The recurring language is personal ("a lovely lady", people
"look forward to" the appointment) alongside straightforwardly professional
("great haircut and colour", "knowledgeable"). Put together, the essence is:
**a proper salon-standard cut and colour, brought specifically to people who
struggle to get to a salon chair, delivered by someone whose regulars
treat the visit as something to look forward to, not just get through.**
That's the thing that should carry the design, not "hairdresser" as a
category.

## Category inspiration (Step 3)

WebFetch being blocked meant relying on WebSearch's synthesis of roundup
articles and guides about hair-stylist/salon website design (CyberOptik's
"Best Hair Stylist Websites", Colorlib's salon website roundup, Mangomint's
and Glossgenius's salon-website blog posts, Ronkot's salon design trends
piece) rather than browsing live competitor sites directly.

Recurring conventions in the category:
- Hero sliders of client hairstyle photos/transformations, used to prove
  versatility.
- Before-and-after photography is treated as the single most important
  trust device.
- Stylist headshots and short bios.
- Booking buttons repeated aggressively throughout the page (header, hero,
  every section), often tied to a live-availability booking widget.
- Soft pastel "spa" palettes, or bold saturated colour to signal
  trend-forward styling.
- Dense service menus with per-service pricing and duration.

**Kept:** a clear hero with a real phone CTA, a genuine services section, a
real trust/reviews section built from paraphrased aggregate sentiment (not
invented quotes), a closing CTA with the real phone number, a footer with
the real area covered.

**Deliberately broken:** no hairstyle hero slider or before/after gallery
(no real photography exists for this mock-up, and stock photos of unrelated
people's hair would misrepresent her actual work); no stylist headshot
(replaced with a simple illustrated silhouette, consistent with both prior
runs' approach of never inventing a specific likeness); no booking button
repeated at every scroll depth, this business runs on a phone call and a
personal relationship, not a self-serve booking funnel, so there's exactly
one calm phone CTA pattern reused, not a dozen; no soft pastel salon palette
and no per-service price list (pricing wasn't confirmed, so, as with both
previous sites, it's deliberately left off and confirmed by phone instead).

## Design decisions

- **Accent colour:** a deep wine/burgundy (`#7c2c46`), chosen because it
  reads as warm and personal, like a favourite armchair or a blanket, which
  fits a business about bringing comfort and normalcy into someone's own
  home, without being the beige+brass "artisan" cliché, the cutesy
  pastel-pink salon cliché, or AI-purple. It's a different hue family
  entirely from both previous runs' sage green and ember orange-red, so the
  three mock-ups don't read as the same template re-skinned.
- **Type pairing:** Frank Ruhl Libre (a literary, characterful serif) for
  headings, Manrope (a clean, warm-leaning rounded sans) for body copy.
  Neither font was used in either previous run (Fraunces + Work Sans,
  Bricolage Grotesque + Karla), and neither is Inter.
- **Spacing/radius system:** an 8px-based spacing scale, but shifted at the
  larger steps (`--space-1` through `--space-8`: 8, 16, 24, 32, 48, 72, 104,
  160), and a three-step radius system (10px small elements, 24px cards,
  48px large shapes) — a different concrete set from both previous runs
  (6/16/32 and 8/20/40), though the underlying "pick a consistent scale"
  method is the same good practice both times.

## The centrepiece (Step 4's "genuinely inventive moment")

**"The whole salon, in one bag."** A pinned, scroll-scrubbed illustrated
scene of an ordinary home room (an armchair by a window, a small side
table), built with GSAP + ScrollTrigger. Every prop is authored in the SVG
at its *final*, unpacked resting position (so the page still looks correct
with no JS or if the animation library fails to load). On load, if motion is
allowed, each prop is displaced back toward a kit bag on the floor via
`gsap.set`; the scroll timeline then animates each one back to its authored
position, in sequence, as if it were being unpacked:

1. The bag's flap opens.
2. A cape unfurls and drapes over the chair back.
3. Scissors and a comb slide out and settle by the table.
4. A hand mirror rises and rotates upright onto the table.
5. A spray bottle pops into place.
6. A warm glow fades in over the window (the room settling, feeling lived
   in, not clinical).
7. A teacup appears with two steam wisps that draw in via
   `stroke-dashoffset` (the kettle Michele puts on, mentioned in her own
   listings as part of the visit).
8. The client's hair itself crossfades from a flat, dull "before" shape to a
   fuller, coloured "after" shape with a highlight streak.
9. A small heart mark fades in near the end, the "people look forward to
   this" feeling made visible.

Four short captions (01 Before, 02 The Visit, 03 The Cut, 04 After)
crossfade in time with the scroll, tracking the same beats.

This is deliberately a different *kind* of moment from both prior runs:
it's neither a single line/shape continuously interpolating along the
scroll (Barking with Style's pulse line) nor a mask sliding over one fixed
illustration (Well Swept's soot reveal). It's an assembly of several
independent objects, each entering a static scene and settling into place
in its own sequence, which is a literal visualisation of the actual
business model: everything a salon chair has, fitted into a bag and
unpacked at someone's own address.

## Mobile and reduced-motion handling

- `prefers-reduced-motion` is checked on load. If set, every `.reveal`
  element is shown immediately, `#cpPinOuter`'s spacer height collapses to
  `auto`, and the illustration is switched straight to its finished state
  (styled hair, warm window glow, steam drawn in, heart mark visible)
  rather than attempting any animation.
- A second safety net was added this run that neither prior site had: if
  the GSAP script tag fails to load at all (blocked CDN, ad blocker, flaky
  connection), the page now detects `typeof window.gsap === 'undefined'`
  and falls back to the same "show everything, no animation" path used for
  reduced motion, instead of leaving every `.reveal` element permanently at
  `opacity:0`. This was caught directly in this run's own testing (see
  Testing below) and is a real robustness gap worth carrying into future
  builds too.
- On viewports under 760px, `gsap.matchMedia` swaps the centrepiece from a
  pinned section to an unpinned one, same technique as Well Swept, so the
  scrub animation still plays as the visitor scrolls past it without
  hijacking touch scroll.

## Testing

cdnjs.cloudflare.com is blocked in this sandbox for both `curl` and
headless-browser traffic (not just WebFetch), same as both previous runs, so
the real GSAP/ScrollTrigger animation could not be watched playing in a
browser here. To still catch real bugs before shipping, I used Playwright
with the sandbox's pre-installed Chromium and found three genuine bugs,
fixed before shipping:

1. **Dark-on-dark contrast bug.** The client's silhouette and hair inside
   the centrepiece were originally drawn in near-black/dark-brown tones
   that were nearly identical to the centrepiece section's dark background
   colour, making the entire figure almost invisible. Confirmed by
   rendering the SVG in isolation and checking element bounding boxes
   against the authored path coordinates, then confirmed the fix with a
   WCAG contrast-ratio check in Python. Fixed by giving the silhouette a
   warm light sand tone and the hair a mid-brown/caramel tone that both
   read clearly against the dark room background and against each other.
2. **Mobile layout overflow in the centrepiece.** At a 390px viewport, the
   illustration and captions sit in a flex row with a fixed gap that adds
   up to wider than the viewport; combined with `overflow:hidden` on the
   parent, this clipped the entire scene, leaving a blank dark rectangle
   with nothing visible. Caught by screenshotting the actual page (not just
   reading the code) at 390px width. Fixed by adding a `max-width:759px`
   media query that stacks the illustration above the captions and caps
   both to a percentage of the viewport width, and simplified the JS so
   mobile sizing is handled by that one CSS rule instead of being split
   between CSS and an inline style set by JS.
3. **No fallback if GSAP fails to load entirely.** Confirmed the whole page
   renders visibly blank (hero text and every section stuck at
   `opacity:0`) if the GSAP script tag doesn't execute at all, since the
   original script assumed GSAP always loads and threw a `ReferenceError`
   on the first line that touched it. This exact scenario is what happens
   in this sandbox (cdnjs blocked), so it was directly observable. Fixed as
   described above under "Mobile and reduced-motion handling".

Validation performed, all passing on the current build:
- A real headless-Chromium render of the actual page with the real GSAP
  script tags present (i.e. exactly what a visitor with blocked/failed CDN
  access would see) shows the full page content, correctly laid out, with
  no console errors.
- A small local stub of the `gsap`/`ScrollTrigger` API (`.set`,
  `.timeline().to()`, `.fromTo()`, `.utils.toArray`, `.matchMedia`) that
  throws if a selector it's asked to animate doesn't exist in the DOM was
  served in place of the real CDN files via Playwright request
  interception. The real, unmodified script ran against it without
  throwing, confirming every element ID and selector referenced in the
  script genuinely exists in the page.
- No horizontal overflow at 1300px or 390px, in the reduced-motion,
  no-GSAP-fallback, and stubbed-script scenarios.
- Full-page screenshot scroll-through at both widths, reduced-motion state,
  confirms all sections (hero, centrepiece, services, about, trust,
  closing CTA, footer) render and there's no overlapping or clipped text.

Ben, given I still couldn't watch the real scroll-scrubbed animation play
in an actual browser with a live internet connection, it's worth a proper
scroll-through yourself before this goes out, same caveat as the last two
runs.

## Honest caveats for Ben to sanity-check

- I could not read individual Facebook review text directly (network access
  blocked), so "What people notice" paraphrases the aggregate 100%/25
  signal and the recurring themes WebSearch surfaced, it isn't quoting
  anyone.
- No pricing is shown anywhere on the site, deliberately, since I couldn't
  verify current rates.
- The email address (michelehunter@hotmail.com) is her own publicly listed
  business contact, not one I invented, but as with previous runs, it's
  worth a quick glance or call before sending anything, standard due
  diligence for scraped contact details.
- The exact villages she covers beyond Haddington itself weren't confirmed
  by name in any source I found (just "East Lothian" generally), so the
  site deliberately says "Haddington and the villages around it" rather
  than naming specific villages I couldn't verify.
- I genuinely could not watch the scroll animation render with a live
  internet connection in this environment (see Testing above), please open
  it and scroll through once yourself before sending.
