# Raising Diamonds Acres LLC: sample website

A one-page sample site for **Raising Diamonds Acres LLC**, a horse barn outside Kenton, Ohio (Hardin County) that gives horseback riding lessons. The barn is owned by Kaylie Snell and Jaycee Murray.

## Contacts
- Phone and text: (937) 441-8166. The owner prefers texts. Her lesson post says: "Not gonna lie, I don't answer phone numbers I don't know."
- Email (public on the Facebook page): kayliesnell08@gmail.com
- Address: 9562 County Road 200, Kenton, OH 43326. Plus code G7XV+9W. The barn's own description is "between Belle Center and Kenton."
- Facebook: https://www.facebook.com/p/Raising-Diamonds-Acres-LLC-61594480917942/ (about 88 followers, Page · Farm)
- No website, Instagram, or sale listings found. No posted hours.

## Sections
Sticky header (gem mark, nav, Text button) · Hero (photo, owners, Text and Call buttons, "text first" note) · Info strip · Riding lessons (ages 5+, own helmet, haul-in welcome, rates as posted) · Around the barn (2 photos with verbatim post quotes) · Meet Lady (barn news) · Getting started (3 steps) · Find the barn (address, Maps, contact list) · Text band · Footer.

Design: Bodoni Moda (display) with Urbanist (body). Palette is night slate, ice blue, and saddle brown. The "diamond" motifs are cut-corner photo frames, diamond bullets and step numbers, and a faceted divider. Light and dark mode.

Sendra tracking: `data-section` on the header, every section, the info strip, the text band, and the footer. `data-track` on every tel:, sms:, mailto:, Maps, and Facebook link. The smb.airoxlab.com script tag sits right before `</body>`. Run with `sendra-track.py`; the labels were checked.

## Data sources
- **Google Maps listing** "Raising Diamonds Acres LLC" (category: Farm). Matched by phone. It is unclaimed and has no hours, website, photos, or reviews.
- **Facebook page** (public, viewed logged out). The intro reads "Horse Barn outside of Kenton Ohio owned by Kaylie Snell and Jaycee Murray." It also lists the address, phone, and email. Posts from Nov 2026 include the "all 4 of these guys" post, the "all this is all ours" post, and the Lady update (20 Nov 2026).
- **Kaylie Snell's public Facebook video post** (23 Jun 2026), which carries the same phone number: "Currently taking students for horse back riding lessons. Located between Belle Center and Kenton Ohio. Anyone ages 5 and up and must provide your own riding helmet. $25/half hour or $35/full hour. If interested pm me or text (937)441-8166 ... You're welcome to haul in your own horse." The site shows the rates labeled "as posted, June 2026, confirm when you text."

## Images (`img/`, all JPEG, checked by magic bytes and by eye)
| File | Source |
|---|---|
| appaloosa-trot.jpg | Facebook page, posted 21 Nov 2026 (hero) |
| appaloosa-bins.jpg | Facebook page, posted 21 Nov 2026 |
| grazing-fence.jpg | Facebook page, posted 21 Nov 2026 |
| paddock-four.jpg | Facebook page, 20 Nov 2026 "all 4 of these guys" post (cropped to the horses) |
| lady-hay.jpg | Facebook page, 20 Nov 2026 Lady post, the "this morning" photo (rotated upright) |

No stock photos are used.

## Excluded
- A photo of a young rider on an appaloosa (likely a child, face visible in profile).
- A phone screenshot of a ShootProof show photo, which is a pro photographer's image.
- A selfie of a man, a pasture shot through a car window, and video thumbnails with text overlays.
- Lady's "day she was found" photo. Someone else took it, and it shows her underweight.
- Lady's breed or age, horse names other than Lady, the new building mentioned on Kaylie's personal profile, kids' names (Emma), and the hay-supplier comment from a follower.
- Same-named businesses: "Raising Diamonds" parenting and business-coach brands, Instagram accounts @raisingdiamonds, @raisingdiamonds_ and @raising_diamonds, YouTube channels, Diamond Detailing (Kenton), and Diamond Acres (NY).
- No testimonials, wins, history, or services beyond what the barn posted.

## Note
The lead form said only "OH" and the 937 area code suggests Dayton. The barn is actually in Hardin County near Kenton and Belle Center (the 937 code reaches up there).

## Deploy
Static: `index.html` + `img/`. GitHub Pages: Settings → Pages → `main` / root.
