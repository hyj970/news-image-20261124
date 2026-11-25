[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/hyj970/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/hyj970/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

# World News — Tuesday 24 November 2026

A one-image summary of the world's news of **Tuesday 24 November 2026**, built for the
make.fun competition `news-image-20261124`. The image is a newspaper-style front page:
a lead story plus four more stories from five regions and beats, with the date shown
prominently in the red banner.

## The five stories

Every story below happened, or was first reported, on Tuesday 24 November 2026.

1. **Huawei found guilty in U.S. criminal trial** — A federal jury in Brooklyn convicts
   China's Huawei on 10 of 12 criminal counts, finding the telecoms giant deceived banks
   about its business in Iran and stole trade secrets from American companies.
   Source: Reuters, 24 November 2026.
2. **China probes a Politburo member** — Shanghai party chief Chen Jining, a member of
   China's elite Politburo, is under investigation, state news agency Xinhua says — the
   fourth member of the top leadership body to be probed since 2025.
   Source: Reuters / Xinhua, 24 November 2026.
3. **Lukashenko offers a joint flight to Moscow** — Belarusian leader Alexander Lukashenko
   proposes that he and Ukraine's President Volodymyr Zelenskiy fly together to Moscow for
   Kremlin talks to end the war, in an interview published on Tuesday.
   Source: Reuters, 24 November 2026.
4. **CIA and spy chief's office breached** — The CIA and the Office of the Director of
   National Intelligence discover a cybersecurity breach that exposed some of their
   unclassified information, the New York Times reports.
   Source: Reuters / The New York Times, 24 November 2026.
5. **WHO: lift the Cuba fuel blockade** — World Health Organization chief Tedros Adhanom
   Ghebreyesus calls for the immediate lifting of the U.S. oil blockade on Cuba, warning
   the measure is putting the lives of children at risk.
   Source: Reuters, 24 November 2026.

## Stories deliberately excluded

These stories were in the news around the same time but were first reported on
23 November 2026 or earlier, so they are **not** 24 November news and were left out:

- Nvidia reinstating Jensen Huang as chief executive, shares up 31% — first reported
  23 November 2026.
- The EU's 22nd Russia sanctions package (60 banks, 70+ shadow-fleet tankers) — proposed
  23 November 2026.
- Russia warning Estonia of "open war" over its planned border closure — 23 November 2026.
- Iran flogging singer Parastoo Ahmadi (74 lashes, Qom) — 23 November 2026.
- Dhaka vowing to jail Sheikh Hasina / extradition push — 23 November 2026.
- COP31 in Antalya ending without agreement — 22 November 2026.
- Drone strike on Kyiv / Dymer — 22 November 2026.
- Delta system fault in Atlanta — 22 November 2026.
- Cikande factory fire — 22 November 2026.
- Drone strikes on Russian ships off Benghazi — 22 November 2026.
- Capture of "El Chapo Isidro" — announced 21 November 2026.

## How the image was made

`render.html` is a hand-written newspaper front page (HTML/CSS, no external images,
no network at render time). It was screenshotted at 1024×1024 with headless Chromium
to produce `entry.png` (210,370 bytes, under the 1 MiB limit). `main.ts` copies
`entry.png` to the output directory and verifies the copy byte-for-byte (size + sha256).

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Run twice into two different directories: both outputs are byte-identical to `entry.png`.

## License

MIT — see [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=xwk0pxbf&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
