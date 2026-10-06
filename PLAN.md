# Emily's Legacy website — plan

Started 6 Oct 2026. A new website for Emily's Legacy, built from scratch, on its own domain. The current `index.html` is a 2023 "Shop and Website under construction" holding page and will be replaced.

What we know today:
- Emily's Legacy was set up by the Marrow family after the loss of their baby girl Emily, born sleeping in 2021. The aim is breaking the taboo on baby loss and supporting other families going through it.
- Donations currently go through GoFundMe: https://www.gofundme.com/f/emilys-legacy
- There's a logo (`emilyslegacy.png`, already uploaded to the Aldwinians Squarespace for the Charity Hub).
- Aldwinians RUFC's Charity Hub (`/charity-hub`) links to it, and will link to the new site once it's live.

---

## Step 1 — Decisions (before buying anything)

- [ ] **Is Emily's Legacy a registered charity, or fundraising through GoFundMe only?** This decides what the site can say ("registered charity no. …"), whether Gift Aid is possible, and which donation options fit.
- [ ] **Who will update the site?** This decides how it's built:
  - **Claude edits it, in this repo** (recommended to start): a fast, free, hand-built site hosted on Vercel or GitHub Pages. Changes are made by asking Claude, as with the Aldwinians pages. Costs only the domain.
  - **The family edits it themselves**: a site builder such as Squarespace or Wix (about £12–20 a month), with drag-and-drop editing.
- [ ] **Shop**: needed at launch, or later? Selling things adds payments, delivery and returns. Suggest launching without it and adding it later.
- [ ] **Email**: do you want an address on the domain (e.g. `hello@emilyslegacy.co.uk`)? Forwarding to an existing inbox is free with most registrars.

## Step 2 — Domain

- [ ] Pick a name. Options to check: `emilyslegacy.co.uk`, `emilyslegacy.org.uk`, `emilys-legacy.co.uk`, `emilyslegacy.org`. `.org.uk` suits a charity or cause; `.co.uk` is the one people tend to guess. Buying both and pointing one at the other avoids lost visitors.
- [ ] Buy it from a registrar that charges a fair renewal price (e.g. Cloudflare, Namecheap or 123-reg; expect about £5–15 a year per name). Watch for cheap first-year deals that renew at a much higher price.
- [ ] Turn on auto-renew and registrar lock, and use an email address you'll keep.
- [ ] Set up email forwarding if wanted (Step 1).

## Step 3 — Content (the family's part — Claude can help draft)

Gather these, in your own words where it matters:
- [ ] **Emily's story**: what you want to share, and how much. Photos you're happy to have public.
- [ ] **What Emily's Legacy does**: what's been raised so far, where the money goes, any projects (e.g. hospital bereavement suites, memory boxes, support groups).
- [ ] **Getting support**: which organisations to point families to. Established ones include Sands (sands.org.uk) and Tommy's (tommys.org); add any local hospital bereavement services or groups that helped you.
- [ ] **Fundraising**: past and upcoming events, ways to get involved, the GoFundMe link.
- [ ] Logo in the best quality available, and any colours you already use.
- [ ] Contact details to publish.

## Step 4 — Design and build (Claude)

Proposed pages (one long homepage plus a few pages keeps it simple):
1. **Home**: a short, gentle introduction, Emily's name, the mission, and clear Donate and Get support buttons.
2. **Emily's story**
3. **What we do**: projects, the total raised, and where the money goes.
4. **Get support**: signposting for families going through baby loss. Linked on every page.
5. **Fundraise and donate**: GoFundMe, events, and how to fundraise for Emily's Legacy.
6. **News and events** (can start as a section on the homepage).
7. **Contact**
8. **Privacy policy** (needed if there's a contact form or analytics).

Design notes: calm and warm rather than "charity campaign"; easy to read on a phone; accessible (good contrast, readable text); quick to load. Support links should always be one tap away.

- [ ] Claude builds a first version in this repo from the content in Step 3.
- [ ] Review together, then refine.

## Step 5 — Launch

- [ ] Hosting: connect this repo to Vercel (or GitHub Pages), and add the domain. HTTPS is automatic.
- [ ] Point the domain's DNS at the host (Claude will give the exact records).
- [ ] Check it on phones, then submit it to Google Search Console so it appears in search.
- [ ] Update the Aldwinians Charity Hub (`aldwinians-webpages/charity-hub.html`) to link to the new site.
- [ ] Update GoFundMe and any social profiles with the new address.

## Later

- [ ] Shop (if wanted) — Shopify Starter, Squarespace Commerce, or Stripe payment links.
- [ ] Newsletter sign-up.
- [ ] If registered as a charity: Gift Aid-friendly donations (e.g. via a charity giving platform).
