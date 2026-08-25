# PRODUCT.md — LP-MAGIA-1

**Status: assumptions inferred from brief (no user interview run — proceeding per user instruction to move fast, reusing prior project's proven structure).**

## Product
Landing page (front-end only, demo/template — no payment backend) selling the "Bursztynowa Komnata" (Amber Chamber) gold collector coin, first piece of AZ Aurum's "Magia Złota" (Magic of Gold) 12-coin subscription collection.

Source content: https://www.azaurum.com.pl/a/kolekcja-magia-zlota

## Audience
Polish collectors / numismatics enthusiasts / gift buyers, same audience as the sister product "Historia Złotych Euro" (LP-test1HZE). Older-skewing, values authenticity, craftsmanship, storytelling, low-risk guarantees.

## Surface & mode
Single landing page, **Persuade** mode (visitor decides and orders). Structure to mirror LP-test1HZE (proven direction, same client/brand): topbar urgency strip, header, promo hero with order form, story section, benefits, gallery, specs table, guarantee, testimonials, FAQ, final CTA, sticky order bar, footer.

## Visual world (assumption, per explicit user instruction to "dopasuj kolorystykę do tematu")
Reuse LP-test1HZE's numismatic premium system (Bitter serif + Work Sans, cream paper background, dark ink sections, gold accents) but retint the accent from cool museum-gold toward **warm amber** — honey/cognac/deep-amber gradient — to match the Amber Chamber subject instead of Vatican-gold. Keep dark ink as the anchor color (still premium/numismatic), swap the metallic gold ramp for an amber ramp.

Images: reused as-is from LP-test1HZE per explicit user instruction ("narazie użyj zdjęć i banerów z poprzedniej wersji") — these are placeholders to be swapped before production (coin/collection is different).

## Brand
AZ Aurum Numizmatyka. Same contact info as sister page: tel 784 622 333 (pon–pt 9–17), sklep@azaurum-sklep.pl. Same logo assets.

## Content facts (from product page)
- Coin: "Bursztynowa Komnata", part of "Magia Złota" collection, 1 of 12 planned monthly coins.
- Price: 429 zł (intro, first coin) vs 499 zł regular — saving 70 zł. Shipping 14,99 zł/coin.
- Specs: gold 9999, 1/100 oz (0,31 g), Ø16mm, nominał 200 dalasi (Gambia), nakład 5000 zestawów, stempel lustrzany (prooflike), rant ząbkowany.
- Includes: moneta, certyfikat autentyczności, szkatuła kolekcjonerska.
- Subscription: kolejne monety co miesiąc (12 łącznie), 14 dni na zwrot każdej, można wstrzymać/anulować w dowolnym momencie.
- Guarantee: 14-day return window.
- Payment: PayU (przelewy, BLIK, karty, Google/Apple Pay) — not implemented in this template.

## Constraints
- Static HTML/CSS/JS only, no backend, no real payment integration (matches LP-test1HZE precedent).
- Must run `/impeccable colorize`-equivalent care on the amber retint, and consider motion/gsap-scroll skills per project CLAUDE.md.
