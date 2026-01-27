Website Rough Draft: [https://maine-beacon.netlify.app/](https://maine-beacon.netlify.app/)

—----------------------------------------------  
Todo:

Remove 2024 death count?  
Remove and replace images with more topical media  
Remove and replace current favicon![][image1]  
Remove all mention of “Maine Winter Survival Initiative”

1. **Replace placeholder impact numbers (0 → real or realistic projections)**  
   The "Projected Impact" section showing **0 Individuals Served**, **0 Survival Kits**, **0 MREs** makes the project look hypothetical or stalled.  
   Please use an emotion evoking cluster of number like “maine days below freezing per year” or current windchill estimate  
2. **Fix broken / placeholder social links (\# anchors)**  
   Facebook, Instagram, LinkedIn all link to \# → they do nothing.  
   Please remove them  
3. **Improve visual hierarchy & emotional impact in the hero section**  
   Current hero is text-heavy with stats below. The cause (extreme cold, deaths, unsheltered people) is emotionally powerful but feels understated.  
   Recommendations:  
   * Lead with a **strong, evocative full-width hero image** (real Maine winter street scene, person in cold with dignity—not generic Unsplash if possible).  
   * Make the headline larger/bolder ("Supporting Maine's Unsheltered" → maybe "Saving Lives in Maine Winters – One Kit at a Time").  
   * Move or re-style the 3 stats (281 unsheltered, \-30° wind chill, 51 deaths) to be **larger, more prominent counters/icons** right in the hero.  
   * Increase contrast/weight on the two CTAs ("Partner With Us" \+ "Learn About Our Mission").  
4. **Mobile responsiveness & readability**  
   Assuming it's built with a framework, test rigorously on actual phones. Common issues on similar Netlify sites:  
   * Text too small on mobile in sections like Core Values  
   * Buttons too close/narrow tap targets  
   * Long paragraphs don't break well → Aim for ≥16px base font, ≥44×44px tap targets, proper stacking on mobile (e.g., stats go vertical).

**Medium Priority (noticeable polish & trust boosters)**

5. **Typography & spacing improvements**  
   * Use more consistent heading sizes (H1 \>\> H2 \>\> H3).  
   * Add more vertical breathing room between sections (current \<hr\> rules feel dated).  
   * Consider a cleaner sans-serif stack if not already (system fonts like Inter, Roboto, or a Google Font like Montserrat for headings).  
   * Core Values list could become a **nice 2- or 4-column grid** on desktop with icons.  
6. **Images & media**  
   The three Unsplash-style photos are okay but generic.  
   → Replace (or supplement) with:  
   * https://unsplash.com/photos/a-lighthouse-on-a-rocky-coast-MfYoFXv1Zc0  
   * [https://unsplash.com/photos/white-speedboat-on-body-of-water-during-daytime-atsXDz\_wk3A](https://unsplash.com/photos/white-speedboat-on-body-of-water-during-daytime-atsXDz_wk3A)  
   * https://unsplash.com/photos/white-motorboat-near-dock-gK9Gljt-1ls  
   * Add captions or alt text that includes keywords for accessibility & SEO.  
7. **Stronger, more frequent CTAs with benefit-oriented copy**  
   "Partner With Us" is repeated but vague.  
   → Try variations like:  
   * "Sponsor a Survival Kit – $75 saves a life this winter"  
   * "Volunteer for Street Outreach"  
   * "Contact Us to Discuss Corporate Partnership"  
   * Add a sticky/floating CTA on scroll ("Donate / Get Involved") if fundraising is live.  
8. **Add immediate trust signals**  
   * 501(c)(3) application pending is honest, but add what *is* ready (e.g., "Organized by veterans", board members, partners).

**Lower Priority (nice-to-haves once basics are solid)**

* Add a simple **progress bar** or "Winter 2025-26 Goal Tracker" if fundraising.  
* Consider subtle animations (fade-in sections) for engagement without being distracting.  
* Dark mode? Not necessary yet—focus on contrast in light mode first.  
* Form integration: If no donation form yet, at least add a "Join Waitlist / Early Interest" form.

Overall the information architecture is logical (Home → About → Programs → Impact → Get Involved → Contact), and the mission is noble and clearly stated. The biggest current risk is that placeholder elements (zeros, \# links) make it feel like a draft rather than an active, trustworthy initiative—which is especially damaging for a life-saving cause.  
Fix the placeholders \+ hero emotional punch \+ mobile readability, and you'll have a much stronger conversion tool.

Add two more founder cards with placeholder text

Nikki as co-founder (the veteran)

Also Libby as co-founder (the grant writing specialist)

[image1]: <data:image/png;base64,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>