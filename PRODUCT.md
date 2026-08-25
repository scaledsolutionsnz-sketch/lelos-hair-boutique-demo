# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS/JS, single `index.html` with inline `<style>` and `<script>`, plus `terms.html` and `privacy.html`. Deployed to Vercel as a static site from a git repo. No build step, no framework. Constrained by the existing demo pipeline, so it must stay a hand-editable static file.

## Users

Women in the north-east Christchurch suburbs (Parklands, New Brighton, Waimairi Beach, Burwood) looking for a stylist they can stay with, rather than a one-off cheap cut. Two arrival situations dominate:

- **Colour clients** who have had colour go wrong or go brassy elsewhere and are researching whether this stylist can actually be trusted with balayage, foils or a corrective tone. They evaluate by looking at photographs of finished hair.
- **Brides and wedding parties** booking months out, who need to know that on-site styling for a group on the morning of the wedding is genuinely offered and genuinely holds.

Secondary: men booking a straightforward cut, and existing regulars using the site only to find the phone number and hours.

The evaluation happens almost entirely on a phone, often at night, often after seeing a photo on Instagram or Facebook.

## Product Purpose

Convert someone who has never met Lelo into a booked appointment. The site is not a booking system and does not process transactions; success is a phone call or an email that names a specific service and a preferred day. A secondary success is an existing client finding hours or the address in under five seconds.

## Positioning

A one-chair private garden salon where the owner is the only stylist. There is no second chair, no assistant, no double-booking. The appointment is not shared with anyone else, and the person who consults on the colour is the person who mixes and applies it, start to finish. A multi-chair high-street salon cannot truthfully make that claim, and neither can a mobile stylist working out of a client's kitchen.

The stylist is award-recognised through the NZARH (New Zealand Association of Registered Hairdressers), with physical trophies photographed on site.

## Operating Context

- Home-based garden studio at a residential address, so the setting itself is part of the offer: quiet, private, plants, no salon noise.
- Open 7 days, 9:00am to 6:00pm, which is unusual locally and is a genuine differentiator for shift workers and weekend clients.
- Weddings are serviced on site at the studio, including bridal parties, on the morning of the event.
- Booking is by phone or email only. There is no online booking, no deposit flow, no client portal.
- Discovery today happens mainly through Instagram and Facebook, where finished-hair photography already does the selling.

## Capabilities and Constraints

Services offered, confirmed:

- Women's cut and style
- Hair colouring: full colour, foils, balayage, creative tones
- Men's cuts
- Hair treatments: deep conditioning and repair
- Blow dry and finish
- Wedding and occasion hair, including on-site bridal party styling

Constraints:

- **No pricing is published or known.** Prices must not be invented or implied anywhere on the site.
- **No online booking exists.** Any "book" action resolves to a phone call or an email.
- Single operator, so availability is genuinely finite; the site should not imply a large team.
- Contact details are fixed: 105 Royal Park Drive, Parklands, Christchurch 8083; 021 484 948; email at hotmail.co.nz (assembled in JS, never printed raw in markup, to limit scraping).

## Brand Commitments

- Name is "Lelo's Hair Boutique"; the stylist is "Lelo".
- Existing logo at `img/logo.png` must be used.
- Instagram `@leloshairboutique` and Facebook `leloshairboutiquee` are the live social accounts; TikTok is a search link only, not a confirmed account.
- Voice is warm and personal, first person plural or singular, not corporate salon-speak.
- House rule for this build pipeline: no em-dashes in visitor-facing copy.

## Evidence on Hand

Real, usable photography in `img/`:

- `hero-1.jpg`, `hero-2.jpg`, `hero-3.jpg` — the studio interior and setting
- `about-lelo.jpg` — Lelo in the garden salon
- `work-1.jpg` … `work-5.jpg` — finished colour, occasion and bridal work
- `work-6.jpg` — the NZARH award trophies, physical proof of the award claim
- `svc-womens`, `svc-colour`, `svc-mens`, `svc-treatments`, `svc-blowdry`, `svc-occasion` — service photography
- `logo.png`

Explicit absences that must not be fabricated:

- **No real Google reviews yet.** The testimonials currently on the site are written examples and are labelled as such. They must stay labelled, or be removed, until real ones exist.
- **No verified star rating or review count.** The incumbent site shows "5.0, loved by local clients" with no substantiation; treat this as unverified.
- Award specifics ARE confirmed, read directly off the engraving in `work-6.jpg`: NZARH winner, Hair by Night Live Event, New Generation Stylist, Canterbury/Westland 2016; NZARH winner, The Day Style Live Event, New Generation Stylist, Canterbury/Westland 2016; NZARH winner, Urban Night Hair, Newcomer, Nelson/Marlborough 2014. Worth confirming the exact wording with Lelo before launch, since one trophy is partly obscured in the photo.
- No prices, no client names, no case studies.

## Product Principles

1. **The photographs are the argument.** A stranger deciding whether to trust someone with their colour is looking at finished hair, not reading adjectives. Copy supports the imagery; it never substitutes for it.
2. **Sell the single chair.** The scarcity and privacy of a one-stylist studio is the thing no competitor can copy. Everything that reads as "busy salon" works against the offer.
3. **Never invent proof.** No prices, no unearned ratings, no unlabelled testimonials. Where proof is thin, show the real trophies and the real work instead.
4. **Phone-first, night-time reading.** The primary visitor is on a phone in low light. Legibility and a reachable call action outrank desktop composition.
5. **Two distinct journeys.** A colour client and a bride want different evidence. Both must find their proof without wading through the other's.

## Accessibility & Inclusion

No client-specific requirement has been established. Baseline obligations apply: the call action must be reachable by keyboard and screen reader, photographic content needs real alt text describing the hair or setting rather than filenames, and body text must clear 4.5:1 against its ground given the low-light phone reading context.
