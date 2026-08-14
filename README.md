# Dhaka Orchid Phenology

A weekly photographic record of ten cultivated epiphytes — mostly orchids — grown in a home collection in Dhaka, Bangladesh.

**Status:** Ongoing. Started 26 July 2026, currently four weeks in. Intended to run across multiple seasons.

---

## What this is

Phenology is the study of recurring biological events and their timing — when a plant initiates buds, flowers, produces new growth, or goes dormant, and how those timings shift from year to year.

Most publicly available phenology data comes from temperate regions with four sharply separated seasons. Bangladesh sits in a tropical monsoon climate, where the year is structured around pre-monsoon, monsoon, post-monsoon and dry periods instead. Orchids are a useful subject in this setting: genera like *Dendrobium* and *Cattleya* have pronounced growth-and-rest cycles that respond to shifts in rainfall, humidity and temperature, so the visible changes are relatively clear week to week.

This is a personal observation log, not a controlled study. The sample is small and the observations are visual. The value is in doing it consistently, over a long enough period for a cycle to actually show up.

## Method

- Every plant is photographed once per week, on Sundays at 16:00
- The fixed day and time keeps light conditions and the weekly interval roughly constant between observations
- Each plant has its own folder; each photo is named by the date it was taken
- Observations are logged in `observations.csv` with the visible stage and a short note

## Repository structure

```
plants/
  01_hoya-pubicalyx/
    2026-07-26.jpg
    2026-08-02.jpg
    2026-08-09.jpg
    ...
  02_hoya-verticillata/
  ...
observations.csv
```

Folders are numbered rather than named, so a plant's identifier stays stable even if its identification is later corrected.

## Plants tracked

| ID | Species | Common name | Family | Notes |
|----|---------|-------------|--------|-------|
| 01 | *Hoya pubicalyx* Merr. | Wax plant | Apocynaceae | Species tentative |
| 02 | *Hoya verticillata* (Blume) G.Don | Wax plant | Apocynaceae | Species tentative |
| 03 | *Rhynchostylis retusa* Blume | Foxtail orchid | Orchidaceae | Genus tentative |
| 04 | *Dendrobium* sp. | — | Orchidaceae | Species unidentified |
| 05 | *Dendrobium* sp. | — | Orchidaceae | Species unidentified |
| 06 | *Dendrobium* sp. | — | Orchidaceae | Species unidentified |
| 07 | *Dendrobium* sp. | — | Orchidaceae | Species unidentified |
| 08 | *Dendrobium* sp. | — | Orchidaceae | One plant divided across two pots |
| 09 | *Epipremnum aureum* (Linden & André) G.S.Bunting | Golden pothos | Araceae | |
| 10 | *Cattleya* sp. | Cattleya orchid | Orchidaceae | Species unidentified |

Identifications marked tentative are my own best determination and may be revised. Where I can only be confident to genus, I have said so rather than guessing at a species.

Two further plants were photographed in the opening weeks but dropped from the set, to keep the collection to subjects I could photograph consistently from the same position each week.

## Why I'm doing this

I'm interested in climate and in applying machine learning to plant health, and I'm building a separate project on automated plant disease classification. Seasonal timing is one of the clearest local signals of a changing climate, and structured, repeated observation is the habit that underpins working with plant data at any scale. Building that habit first, by hand, on ten plants, seemed like the right order to do things in.

## Limitations

These are worth stating plainly, because they bound what the data can show:

- **Cultivated, not wild.** These plants are watered, fed and positioned by me. They respond to that care as much as to season, so this is not a clean climate signal.
- **Small sample.** Ten plants in one collection, seven of them orchids and five of those the same genus. Not representative of anything beyond itself.
- **Qualitative.** Observations are visual. Nothing is measured — no growth dimensions, no bloom counts, no microclimate logging.
- **Short record so far.** Phenology needs seasons, ideally years. Four weeks establishes the method, not a cycle.
- **Uncertain identifications.** Several plants are identified only to genus.

## Planned additions

- Continued weekly observations through the monsoon and dry seasons
- Species-level identification for the *Dendrobium* and *Cattleya* plants, ideally when they next flower
- Simple environmental context per observation, drawn from local weather records

---

*Inspired by the approach of [Project BudBurst](https://budburst.org/), a citizen-science phenology network, scaled down to a personal log.*
