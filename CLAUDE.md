# Working in this repo

## Don't ask permission

Morgan wants follow-through without check-ins (Oct 31). When a change obviously implies follow-up work (updating Drive copies, the index, Jarvis, CLAUDE.md, calendar), just do it and report what was done. Only ask when Morgan's intent is genuinely unclear (e.g. which price is right). Morgan repeated this Nov 1: don't end replies with "want me to…?" offers. If a detail is missing (a date, a time), pick the most likely option, do it, and say what you assumed so he can correct it.
When Morgan says "add this to the calendar / Drive / Jarvis" (or anything like it), do it immediately; never ask first or ask him to confirm.
**No emojis in customer texts** (Morgan, Nov 2): every text, pitch or reply written for Morgan to send to a customer or lead must have zero emojis.
**Never ask permission to optimize anything, ever** (Morgan, Nov 1, said three times). No "tell me and I'll…", no "want me to…", no confirmation questions. Make the best call, do it, report it in one line, and note any assumption so he can correct it.

## Always upload new files to Google Drive

Morgan wants every file you make or update uploaded to Google Drive as soon as it's done. Don't wait to be asked.

- **Folder:** "Coastline Auto Detailing – Jarvis Files" (id `1gV0QRt1BfOB8OyDNqaCH35dn8d44Xb5u`, https://drive.google.com/drive/folders/1gV0QRt1BfOB8OyDNqaCH35dn8d44Xb5u)
- **Spreadsheets (.xlsx):** upload as a Google Sheet. Use `create_file` with `text/csv` content; it converts, and formulas work.
- **Word docs and plans (.docx / .md):** upload as a Google Doc. Use `create_file` with `text/html` content.
  - Put the copyright line at the top of every plan: "© 2026 Morgan / Coastline Auto Detailing. All rights reserved. Confidential — do not copy or share without written permission."
- **Updating a file that's already in Drive:** the Drive tools can't edit an existing Doc or Sheet. Upload a new copy and tell Morgan which one is the latest.
- **Send the Drive link** in your reply with each file.
- **If the Google Drive connector isn't connected,** say so right away and give the file here instead. Morgan can reconnect it at claude.ai → Settings → Connectors.
- **Google Sheets drops a leading apostrophe** from a cell (it reads it as "text"). Start quoted text with curly quotes “ ” instead of '.
- **Don't edit the contents of Morgan's own sheets** (the Rapid Reach "PPC LP Leads" sheet, Tech Standards) unless asked. Morgan gave full access to organize Drive and Calendar (Sep 26): moving/renaming is fine.
- **Google Calendar layout:** daily blocks 11:15 AM routine, 2 PM lead check, 6:30 PM post/reviews/log; Sunday 7 PM weekly review; last day of month 8 PM month-end close. Deadlines are red all-day events, Amelia's vet items are green all-day events.

## Pricing (Nov 1)

Three packages (Essential was dropped Nov 1 to keep it simple): **Basic $185** (car-wash crowd: exterior hand wash, wheels/tire shine, quick vacuum, wipe-down, windows), **Standard $250** (the full detail: full interior incl. trunk, seats/carpets spot-treated, dash/console/vents, door jambs, mats, inside windows + hand wash, wheels & wells, tire shine, bug & tar, windows, spray sealant), **Luxury $330** (Standard + shampoo of seats/carpets/mats, leather, hand wax, trim, engine bay). **One price for every vehicle** (confirmed Nov 1). Drive menus, price sheet, sub doc, pricing strategy, closing scripts and Jarvis are all on this lineup. Subs (Austin, Mo): $25 Rapid Reach fee off the top, then 60% sub / 40% Morgan (keep $64 / $90 / $122). **The $25 Rapid Reach fee applies only to jobs from Rapid Reach ads**; website, direct, referral and Meta bookings have no fee, so the sub gets 60% of the full price (Morgan, Nov 2). Jarvis has a "Lead source" field on each job for this. Christina (Nov 1, $425, Mo 65%) was a direct booking: Mo $276.25, Morgan $148.75. Morgan also details jobs himself (keeps price − $25 − ~$15–20 supplies). Pitch Luxury first for "detail" callers; Basic for "car wash" callers with "for $65 more, Standard does the full detail." $10k ≈ 38 jobs at the usual mix. **Thanksgiving Special $225 (through Nov 25, the Meta ad offer):** Standard detail + leather clean/condition, spray wax, streak-free glass, tire shine + trim dressing, holiday scent (premium touches that add ~20–30 min, no full shampoo); shampoo +$75 and pet hair +$50 as on-site upsells. Keep $80 on a sub job, ~$183 on Morgan's own job. Add-ons: fixed list, sold on site after a walk-around, approved before work starts, never charged after.

## Ads (Nov 1)

**All Google advertising (LSA + Search) is run by Rapid Reach** ($25 per completed job); Morgan doesn't manage Google ads himself. Morgan runs **Meta (Facebook/Instagram) ads at $30/day, launching Nov 5**: one Leads campaign with 3 ad sets at $10/day each (GA: Loganville +20 mi; DE: Wilmington +12 mi; PA: Glen Mills +12 mi; radii kept apart so DE/PA don't overlap), Thanksgiving Special $225 offer, leads tagged by state in GoHighLevel and routed to the local sub. Meta leads carry no Rapid Reach fee, so subs split the full price 60/40 (red all-day calendar event with the launch checklist) (Morgan's call, replacing the earlier "no Meta until 2027" plan). Calendar check on Nov 19 7:30 PM (2 weeks after launch), judged per state: keep if cost per booked job is under $60, pause if fewer than 3 bookings after ~$400. Nov 1: Morgan's Meta ad account showed as restricted (he fixed it the same day); told him not to open a new profile to get around it (Meta bans for circumvention) and to check facebook.com/accountquality, request review, verify ID, or ask Rapid Reach to run Meta through their agency account.

## Scheduled agents (updated Nov 1)

All agent prompts carry the three packages, Austin + Mo at 60/40, the $10k November goal and 120 reviews by Jan 1. New: "Overnight Ops: morning brief" (daily 5:07 AM ET) and "Weekly Scorecard" (Sundays 6:43 PM ET); both need Google Calendar/Drive connectors added in claude.ai → Routines. "Nightly Calendar Optimization" (3 AM) and "Nightly Revenue Prep" post into another session and can only be edited there; Revenue Prep still points at old sheet IDs.

## Drive folder layout

Inside the main folder:
- `00 START HERE – Coastline Index` (Google Doc, id `1jVAW_w8-mdsjdw1I97ab6ESX2eNIpyZffahgM9cEhdI`): links to every file. Add a link here when you upload a new file.
- `1 – Goals & Plans` (id `1in_g-Gjbc0RusUmNo-3aPeWv4Fg5TSrG`): goals, monthly/seasonal plans, growth plan.
- `2 – Sales & Scripts` (id `1s_lC7XjS8tqpHAm3dULYPBGyWvfscL2i`): pitches, objection scripts, research.
- `3 – Glen Mills PA (2028)` (id `1aGEOXCNVPkcJVQNOnzta0BcEl2rFYmre`).
- `4 – Team & Techs` (id `1sh5F3vrs5SsXnSqlfQV-ax6F2aB5JaaX`): tech standards (`01 Tech Standards.xlsx`, Morgan's own file; don't edit its contents unless asked), hiring, payouts.
- `9 – Archive (old versions)` (id `1H6muumfRy9ePceSsau-6Y9p8OXTJa-iQ`): move replaced versions here and prefix the title with "OLD –".

Upload new files straight into the right subfolder and number them to match (e.g. "07 …"). The Drive tools can't edit the index doc, so when a file is added, upload a new index copy, move the old one to Archive, and update the id above.

## Files already in Drive

| Local file | Drive copy |
| --- | --- |
| `Glen_Mills_Launch.xlsx` | [Google Sheet](https://docs.google.com/spreadsheets/d/1cIAIhb9IQUuolIezsY6FZdarO4C3XY4dMs6OWXmUFYo/edit) |
| `Coastline_Pitches_and_Automations.xlsx` | [Google Sheet](https://docs.google.com/spreadsheets/d/15iTllTVpW3FtbSztmqXDFJ3opXGQ3tdMHwcc8o-SWrQ/edit) |
| `Coastline_Glen_Mills_Business_Plan.docx` | [Google Doc](https://docs.google.com/document/d/1YxEa7EFyhGDmxe_Gy4J2vKah4pVIjl7YeVfXE1s2Oo8/edit) |
| `Coastline_Growth_Plan_50k_100k.docx` | [Google Doc, latest (Oct $10k)](https://docs.google.com/document/d/1i22UXCEZYN6QyXVFFH_DgAgh7iZHKKxLEgHlMSs7FRg/edit). |
| `WINTER_PLAN.md` / `Coastline_Winter_Plan_Nov_Feb.docx` | [Google Doc, latest (Sep 25: $250 / $199 + margins)](https://docs.google.com/document/d/1urTsDgSu0Tou3H2tH_ZNlHjsMqpvk_hnYdo7TuyHJpM/edit). Old copy is in Archive. |
| `Coastline_Closing_Scripts.xlsx` | [Google Sheet: 02 Closing Scripts & Close Rate Tracker (Basic / Standard / Luxury), latest (Nov 1)](https://docs.google.com/spreadsheets/d/1n6IsLqPPoOZijyZjVZfb-IU9N_xabEvAfsb6OcMa9r4/edit). All four tabs stacked in one sheet. Old copies in Archive. |
| `Coastline_October_10k_Goals.xlsx` | [Google Sheet, latest (Oct 10: $199/$179/$165 pricing)](https://docs.google.com/spreadsheets/d/1dLIzJxbHy3ohB2vT-YoNqLT5DtfgsDleMCUFMI4cbNU/edit). Old copy is in Archive. |
| `OCTOBER_10K_PLAN.md` | [Google Doc](https://docs.google.com/document/d/1YXYYBKGPtkUKmASXaFF1dU1bLPyCpCq1Omp5gX78tBI/edit) |
| `DETAILING_SALES_RESEARCH.md` | [Google Doc](https://docs.google.com/document/d/1BdDANzrit30r0NDMgxexM83Ka-cXCMnVgEFUZ99NHB0/edit) |
| `Coastline_Close_On_The_Spot.xlsx` | [Google Sheet](https://docs.google.com/spreadsheets/d/1ahADR3LjdXA3oX79gaVlgu9Nn2KBt0v2RXfpYsZYfkM/edit) |
| `Coastline_Goals_Sep_Dec_2026.xlsx` | [Google Sheet: 02 Goals Sep-Dec 2026 (Nov 5: $425 done + $1,429 booked), latest](https://docs.google.com/spreadsheets/d/1Dw84hBHggeJYZCSr0x5glPXXvNeMOumLxa70RSqRlFI/edit). October closed at $7,419; November goal $10k (stretch $11k, ~38 jobs, 90 leads); November so far $425 done = Christina, 2 cars, done by Mo at 65%; $225 booked = Erica Jones, 2019 Kia Sorento, Thanksgiving Special, Nov 4 (PA, website lead, no fee). $225 booked = Ram 1500, Covington GA, Thanksgiving Special, Thu Nov 5 1 PM (Google LSA lead, $25 fee). $300 booked = Isabel Casey, 2022 Subaru Impreza, Wilmington DE, Thanksgiving Special + shampoo (Google LSA lead); postponed Nov 3 to next week, tentative Tue Nov 10 10 AM, follow-up Fri Nov 6. $225 booked = Russ, (828) 380-9521, invoice paid Nov 3, 2366 Tree Arbor Way, Marietta GA (gate #9521), Thanksgiving Special, Thu Nov 5 12 PM (confirmed). $229 booked = Bear DE, (402) 675-6374, interior detail + back-seat spot cleaning with itemized receipt, Thu Nov 5 6 PM (Google LSA lead). $225 booked = C7 Corvette, Thanksgiving Special, Thu Nov 5 10 AM (customer/source not recorded). Reviews 40 → 120 by Jan 1. Older copies in Archive. Team: Austin + Mo (60/40 standard). |
| `SPRING_2027_PLAN.md` | [Google Doc](https://docs.google.com/document/d/1z9_5Ig5puf1p66wOCu4POaCxyDAkSUWJm_SJeZ_6xkA/edit) |
| `Coastline_Daily_Game_Plan.xlsx` | [Google Sheet: 07 Daily Game Plan, latest (Oct 10: name removed)](https://docs.google.com/spreadsheets/d/1-A16mO2G7yRFmXkZyhOahpbYYrKiWaoqBEQTlyQ1_R8/edit). Old copy is in Archive. |
| `Coastline_Price_Sheet.xlsx` | [Google Sheet: 05 Price Sheet + Profit Calculator (Basic / Standard / Luxury), latest (Nov 1)](https://docs.google.com/spreadsheets/d/18jFL65PgIXTJDgBuJWpPCnsWmhJGHgui9z3Svxppgqg/edit). Old copies in Archive. |
| `PRICE_MENU.md` | [Google Doc: 06 Customer Price Menu (Basic / Standard / Luxury), latest (Nov 1)](https://docs.google.com/document/d/1Hw5Xhv8X_6ReNh0z6MrzS7UUD0cR8uPAZKgxMZ5REnc/edit). Old copies in Archive. |
| (Nov 1) | [Google Doc: 08 Pricing Strategy: Basic / Standard / Luxury (one price)](https://docs.google.com/document/d/1TaQt_pdRnNQyWx-fRXQ5OFnBUf-WrDvJHW6B0Ig0CIQ/edit), latest. Old copies in Archive. |
| (Nov 1) | [Google Doc: 09 $10k to $30k to $100k: Steps and Numbers (Standard / Luxury)](https://docs.google.com/document/d/1YfA1l2cB1Xl1vP8B3s9-GBlpPEFQmPKDWju7niQx2ec/edit), latest. Older 09 copies are still in 1 – Goals & Plans. |
| (new, Oct 12) | [Google Doc: 10 Top 3 Focus: Reviews, Response Rate, Radius](https://docs.google.com/document/d/1GS8xScSeyXcnGRuJwUtbh4FQnPiv_UnsJ9og7rbLNig/edit) |
| (Nov 1, in 4 – Team & Techs) | [Google Doc: 11 Subcontractor Pricing + Payout Split (Basic / Standard / Luxury)](https://docs.google.com/document/d/1Tm3nT8fpxMxy2JqTPVpzdd_agHtrlf-96Hudhebe--E/edit), latest. Old copies in Archive. |
| (Oct 21, in 4 – Team & Techs) | [Google Doc: 12 Subcontractor Expansion Plan – 20 Subs by May](https://docs.google.com/document/d/1Ead9SsqFaDHKkce1hyOHq7e9aYPlrJbDUAEmQDAflEI/edit) |
| `REVIEW_PLAN.md` | [Google Doc: 13 Review Plan: 120 Google Reviews by New Year (Oct 31)](https://docs.google.com/document/d/1Fq-zXKpVRV91O8rr410V8H10llJNtZBMA67O_PXaxQA/edit), in 1 – Goals & Plans |
| `NOVEMBER_10K_PLAN.md` | [Google Doc: 14 November $10k Plan (Nov 1)](https://docs.google.com/document/d/1HtHOVT8KSaD5DwRzXyNRUrZqIV12HigdF4XYeBMgL_A/edit), in 1 – Goals & Plans. Daily red all-day calendar event Nov 1–30 plus Nov 2 10:30 AM past-customer text. |

Add a row here whenever you upload a new file.
