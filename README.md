# Sum up 23 November's world news in one image

Entry for the make.fun bounty **“Sum up 23 November's world news in one image”**
(`news-image-20261123`, $100 in USDC, 50 paid places, ends 25 Nov 2026 00:00 UTC).

## What the image shows

A one-page newspaper front page for Monday 23 November 2026:

- **COP31 collapses with no deal** — the longest UN climate conference in
  history, held in Türkiye, ends divided over fossil fuels and money.
- **Ukraine war** — Russian strikes kill at least 15 near Kyiv; overnight
  attacks hit Kryvyi Rih, damaging homes, a hospital and schools.
- **Iran / Middle East** — Trump says no acceptable Iran deal yet and strikes
  may resume after New Year; Tehran accused over a hit on Bahrain; a food
  truck is hit in Gaza.
- **Washington** — Democrats win the biggest House majority in decades.
- **United Nations** — the UN chief urges global AI regulation at a Barbados
  summit; fighting in DR Congo disrupts the Ebola response.
- Footer: West Bank settler arson condemned; UN urged to probe Libya port
  attacks; Xi, Trump and Putin meet for first trilateral talks.

News checked on 23 Nov 2026 against that day's reporting, including
Just Security's Early Edition for 23 November 2026, UN News Today
23 November 2026, and South China Morning Post world headlines for
23 Nov 2026.

## How it runs

```sh
python3 main.py
```

Writes `/output/entry.png` (1024×1024 PNG, under 1 MiB). The program uses
only the Python standard library, no network, and copies `asset.png`
byte-for-byte, so two runs always produce identical bytes.
Set `ENTRY_OUTPUT=/some/path.png` to test locally with a different
destination.

## Licence

MIT — see `LICENSE`.
