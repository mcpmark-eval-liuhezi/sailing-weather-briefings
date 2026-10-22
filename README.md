# Sailing Weather Briefings — Fushan Bay, Qingdao

Weekly marine weather briefings for our community sailing program's novice training waters off **Fushan Bay (浮山湾), Qingdao, Shandong, China**.

- **Training waters (open water):** approximately `36.03°N, 120.37°E`, just south of the Fushan Bay waterfront
- **Marina / program base:** Fushan Bay waterfront (Olympic Sailing Center area), approximately `36.05°N, 120.37°E`
- **Timezone:** everything in this repository is written in **Asia/Shanghai (UTC+8)** — the timezone the coastal site actually falls in. It is the same clock as Beijing time (China does not observe daylight saving), so instructors never need to convert.

## The weekly briefing series

Every week we publish one briefing as `briefings/this-week.md` on a dedicated branch named after that week (for example `week-2026-10-19` for the week of Monday 19 October 2026). The briefing is then opened as a pull request into `main` for the head coach to review — **a briefing only counts once it has been through a pull request she has reviewed.**

Each briefing covers the coming five days and, for every day, sets out:

- significant wave height, swell height, swell direction and swell period for the training waters, plus tide data where the source offers it;
- the wind forecast for the marina itself;
- sunrise and sunset;
- any active weather warnings covering the area;
- the GO/NO-GO verdict for the novice group;
- a short "notes from the community" section drawn from open-source marine-weather and sailing race-management projects on GitHub.

## The GO/NO-GO rule

A day is **NO-GO** for the novice group if **either**:

- the **significant wave height** for that day **exceeds 1 m**, or
- the **wind tops 20 km/h**.

Otherwise the day is **GO**.

Two standing principles:

1. **Numbers, not guesses.** Verdicts are applied only to the figures actually retrieved in that week's briefing — no guessing, no placeholders.
2. **No data means no-go.** If the weather source returns no wave or wind figures for a day, that day is held as NO-GO for the novice group until the feed can be re-checked and the briefing updated.

## Similar organizations

Other sailing- and maritime-related organizations doing open-source work on GitHub:

- **[OpenCPN](https://github.com/OpenCPN)** — the long-running open-source chartplotter and marine navigation project (electronic charts, AIS, GRIB weather and weather routing); the [main repository](https://github.com/OpenCPN/OpenCPN) has been maintained since 2010.
- **[Signal K](https://github.com/SignalK)** — the open marine data standard and server ecosystem that lets boats share instrumentation, position and weather data across devices and applications.
- **[Sailing Yacht Research Foundation](https://github.com/sailing-yacht-research-foundation)** — open-source sailing performance, race analytics and handicapping research.
- **[bareboat-necessities](https://github.com/bareboat-necessities)** — open-source hardware and software for cruising sailboats (chartplotter, AIS, instrumentation).

## Questions

If anything in a briefing is unclear — a GO/NO-GO call, a number that looks off, the tide or swell detail — **ping the duty officer**. They own the feed and can re-run the forecast or explain the reasoning behind a day's verdict before you take the novice group out.
