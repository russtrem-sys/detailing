# Russ's Sovereign Detailing

Part of [[Business Websites]] (my own business, not a client)

## Status
- Stage: Website built Oct 4, 2026, not deployed yet
- Next step: upload to Cloudflare Pages, then confirm the FormSubmit email

## Business info
- Service: Mobile car detailing (I come to the customer)
- Service area: Sovereign Oaks community first, greater Asheville, NC, fully mobile
- Phone: (910) 945-8635
- Email: ruusem123@gmail.com

## Prices
| Package | Price |
|---|---|
| Exterior | $75 |
| Interior | $65 |
| Full Detail | $125 |
| Large SUV or large truck | +$15 on any package |

- Full Detail saves $15 compared with booking Exterior + Interior ($140)

## Site details
- File: Sites/russs-sovereign-detailing/index.html (in this vault)
- Look: forest green and cream with a gold accent, easy-to-read fonts
- Sections: top banner, packages, how it works (3 steps), service area, quote form, contact
- Animations: fade-in on load, sections slide in on scroll, shine sweeps across the car, cards lift on hover, estimate pops when it changes. Turned off automatically for people who set "reduce motion"
- Phones: a Call / Get a quote bar sticks to the bottom of the screen
- Quote form asks: name, phone, email, package, vehicle size, year/make/model, preferred day, location, notes
- Form shows a live price estimate (package + $15 if large) and includes it in the email
- Form delivery: FormSubmit (free, no account) sends each request to ruusem123@gmail.com. Has a hidden spam trap
- The form only sends from the real website, not from the Claude preview
- Host: Cloudflare Pages (free)
- Domain: TBD (idea: russsovereigndetailing.com)

## Checklist to go live
- [ ] Upload the folder with index.html to Cloudflare Pages (or use a GitHub repo for auto-deploy, see [[Claude Start Here]])
- [ ] Send one test quote from the live site
- [ ] FormSubmit emails ruusem123@gmail.com a confirmation link. Click it once. After that, quotes arrive normally
- [ ] Send a second test quote and make sure it arrives
- [ ] Optional: buy a domain and add it under Custom domains
- [ ] Optional: add real before/after photos of my work
- [ ] Share the link in Sovereign Oaks Facebook groups / Nextdoor

## How this was built (process to reuse for clients)
1. Claude asked questions first: business name, how quotes should reach me, style, service area
2. Claude built one index.html file with everything inside it
3. Claude published a private preview and saved the file plus this note to the vault
4. I upload to Cloudflare Pages and confirm FormSubmit

## Lessons for future sites
- Same layout works for any local service business: banner, services and prices, how it works, area, quote form, contact
- FormSubmit is the easiest free way to get form emails on Cloudflare Pages (no server needed)
- Ask about name, form delivery, style and service area up front so nothing has to be redone

## Log
- 2026-10-04: Built the website with Claude, saved to vault
