# TouristNetTR Hotel Lead Run — 2026-06-14 20:59

## Result

Committed 10 hotel-only B2B lead candidates for Türkiye.

CSV path:
`leads/hotel-leads/2026-06-14/2059/touristnettr_hotels_10_2026-06-14_2059.csv`

Report path:
`reports/hotel-leads/2026-06-14/2059/touristnettr_hotels_10_2026-06-14_2059.md`

## Deduplication check

Target repository search for previous `hotel-leads` / `touristnettr_hotels_10` outputs returned no existing lead files. Repository size was effectively empty at the time of this run, so no prior hotel names, website domains, phones, Instagram accounts, or emails were available to deduplicate against.

## Sources searched / used

- Akra Hotels official contact page: `https://www.akrahotels.com/en/contact/`
- Accor official ibis Adana page: `https://all.accor.com/hotel/8028/index.en.shtml`
- Hilton Istanbul Bosphorus reference result with official Hilton website: `https://en.wikipedia.org/wiki/Hilton_Istanbul_Bosphorus`
- Swissôtel The Bosphorus reference result with official website: `https://en.wikipedia.org/wiki/Swiss%C3%B4tel_The_Bosphorus`

## Lead list

| # | Hotel | City | Segment | Confidence | Contact mode |
|---:|---|---|---|---:|---|
| 1 | Akra Antalya | Antalya | City resort / upscale hotel | 96 | Website / official contact page |
| 2 | Akra V | Antalya | Urban hotel accommodation | 92 | Website / official contact page |
| 3 | Akra Kemer | Antalya / Kemer | Resort hotel | 97 | Website / official contact page |
| 4 | Akra Sorgun | Antalya / Manavgat | Resort hotel | 97 | Website / official contact page |
| 5 | Akra Fethiye | Muğla / Fethiye | Resort hotel | 97 | Website / official contact page |
| 6 | Akra Fethiye The Residence | Muğla / Fethiye | Premium hotel-branded residence accommodation | 95 | Website / official contact page |
| 7 | Akra Didim | Aydın / Didim | Resort hotel | 94 | Website / official contact page |
| 8 | ibis Adana | Adana | Business/city hotel | 88 | Website / official Accor page |
| 9 | Hilton Istanbul Bosphorus | Istanbul | Five-star international chain hotel | 82 | Website-only |
| 10 | Swissôtel The Bosphorus Istanbul | Istanbul | Luxury international chain hotel | 84 | Website-only |

## Validation notes

- All 10 records are hotels or hotel-branded accommodation businesses in Türkiye.
- Agencies, DMCs, transfers, villas, property managers, real estate, restaurants, shops, WU/exchange/communication shops and unrelated businesses were excluded.
- Priority regions covered: Antalya, Muğla/Fethiye and Istanbul. Aydın/Didim was included as a coastal foreign-tourist resort market. Adana was included as a lower-priority but confirmed international hotel-brand record to reach exactly 10 honest records.
- Direct email and phone values were visible in some retrieved sources, but the first GitHub write containing direct contact fields was blocked by safety checks. To keep the run committed and avoid inventing data, the committed CSV leaves phone/email blank and points to the exact source pages for manual extraction.

## Expansion recommendation

Next run should diversify away from a single brand cluster and target:

1. Cappadocia cave hotels: Uçhisar, Göreme, Ürgüp.
2. Bodrum/Marmaris/Fethiye luxury hotels not already included.
3. Istanbul boutique/luxury hotels with source-visible direct contact pages.
4. Thermal hotels in Bursa, Afyon and Denizli.

