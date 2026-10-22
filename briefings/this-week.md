# Marine Weather Briefing — Week of 19 October 2026

**Community sailing program · training waters off Fushan Bay, Qingdao, Shandong, China**
**Prepared Thursday 22 October 2026, ~15:00 local — all times in Asia/Shanghai (UTC+8)**

---

## Site and timezone

- **Training waters (open water, where the novice group sails):** ~36.03°N, 120.37°E, just off the Fushan Bay waterfront
- **Marina / program base:** Fushan Bay waterfront, ~36.05°N, 120.37°E
- **Timezone:** the coastal site falls in **Asia/Shanghai, UTC+8** — the same clock as Beijing time. China does not use daylight saving, so no conversion is ever needed. Everything below is in that zone.

## The safety rule (unchanged)

A day is **NO-GO** for the novice group if the **significant wave height exceeds 1 m** **or** the **wind tops 20 km/h**. Otherwise it is **GO**. Where the source returns no numbers for a day, we hold that day as NO-GO until the feed can be re-checked.

## Warnings

**No active weather warnings.** The alerts feed covering the Fushan Bay area (checked 22 October 2026, ~15:00 local) returned no government warnings for the site. Nothing to flag to instructors.

## Five days at a glance

| Day | Significant wave height | Wind (marina) | Verdict |
|---|---|---|---|
| Thu 22 Oct | 0.1–0.2 m | 20.2 km/h | **NO-GO** (wind) |
| Fri 23 Oct | no wave data returned | 23 km/h | **NO-GO** (wind) |
| Sat 24 Oct | no wave data returned | no wind data returned | **NO-GO** (no data — hold) |
| Sun 25 Oct | no wave data returned | no wind data returned | **NO-GO** (no data — hold) |
| Mon 26 Oct | no wave data returned | no wind data returned | **NO-GO** (no data — hold) |

## Data availability note (please read)

Our marine and regular forecast feeds both cover five days, but this week they only returned usable figures for **Thursday and (wind only) Friday**. The wave data for Friday through Monday and the wind data for Saturday through Monday did not come back from the source. Rather than guess, those days are held as **NO-GO** under our standing "no data means no-go" principle, and the duty officer should re-run the feed before any of them is reopened. Sunrise and sunset below are complete for all five days.

---

## Thursday 22 October

**Verdict: NO-GO for the novice group** — wind tops the 20 km/h limit.

- **Sea state on the training waters:** significant wave height **0.1–0.2 m**, well inside the 1 m limit. Swell height **0.1–0.3 m**, from the **SE (124°)**, swell period mostly **2.8–2.9 s** with one **13 s** long-period reading around 03:00. Water temperature **21.2 °C**. (Figures are the overnight-to-morning hours the feed returned; the on-water day wind in that same feed peaked at 13 km/h.)
- **Wind at the marina:** the marina wind forecast peaks at **20.2 km/h** — just over our 20 km/h ceiling, so the day is a NO-GO even though the water is flat. Gusty at times.
- **Sunrise / sunset:** 06:11 / 17:14.
- **Tides (from our marine source, which does offer tide data):** HIGH 02:06 (3.38 m) · LOW 08:07 (1.48 m) · HIGH 14:01 (3.15 m) · LOW 20:17 (1.00 m). Tidal range is roughly 2 m, which matters for the slip and the launch window.
- **Warnings:** none active.

*What happened:* calm water but the wind number edged just past the limit. With novices, we call it as the rule says. A morning-only window before the breeze builds is a question for the head coach, not for this briefing.

## Friday 23 October

**Verdict: NO-GO for the novice group** — wind tops the 20 km/h limit.

- **Sea state on the training waters:** **no wave data returned by the feed for this day** — treat as unverified.
- **Wind at the marina:** forecast peak **23 km/h**, SE, breezier than Thursday, with gusts into the high 20s km/h around dawn and mid-morning. Overcast to sunny, around 16–18 °C.
- **Sunrise / sunset:** 06:12 / 17:12.
- **Warnings:** none active.

*What happened:* clearly over the wind ceiling. NO-GO on the wind alone; the missing wave data only reinforces it.

## Saturday 24 October

**Verdict: NO-GO for the novice group (held — no data).**

- **Sea state:** no wave data returned.
- **Wind:** no wind figures returned.
- **Sunrise / sunset:** 06:13 / 17:11.
- **Warnings:** none active.

*What happened:* nothing to verify against the rule, so the day stays closed for the novice group until the feed is re-run and this briefing is updated.

## Sunday 25 October

**Verdict: NO-GO for the novice group (held — no data).**

- **Sea state:** no wave data returned.
- **Wind:** no wind figures returned.
- **Sunrise / sunset:** 06:14 / 17:10.
- **Warnings:** none active.

## Monday 26 October

**Verdict: NO-GO for the novice group (held — no data).**

- **Sea state:** no wave data returned.
- **Wind:** no wind figures returned.
- **Sunrise / sunset:** 06:15 / 17:09.
- **Warnings:** none active.

---

## Notes from the community

This week we looked at **OpenCPN** (https://github.com/OpenCPN/OpenCPN), the open-source chartplotter and marine navigation project — an open-source marine-weather project with active public discussion threads (its Discussions tab is busy, including the "Weather_Routing and OpenCPN Development Planning" thread at https://github.com/OpenCPN/OpenCPN/discussions/4485).

**One useful thing we learned about reading swell and wave forecasts**, from the WaveWatch III (WW3) wave-model work documented in PR https://github.com/OpenCPN/OpenCPN/pull/4696 and its linked issue https://github.com/OpenCPN/OpenCPN/issues/4762: the WW3 model splits the sea into three families of parameters — **combined waves**, **wind waves** and **swell waves** — each with its own height, direction and period. The single "significant wave height" number most forecasts lead with is the *total significant height of combined wind waves and swell*: waves generated by the **local wind** stacked on top of **swell, the long-period waves that have travelled in from distant storms**. Two practical takeaways for reading our briefing:

1. **The same height can be two very different days.** A small combined height made of short 2.8–3 s wind chop (locally generated, dies out fast) is a different day from the same height arriving as a 13 s long-period swell. That is exactly why we report swell height, direction and period alongside the significant wave height — and why Thursday's lone 13 s / 0.3 m swell reading is worth a second look even though the combined height stays tiny.
2. **Whenever a source splits the swell out separately, check it.** The combined number alone can hide a long-period groundswell that matters more to small boats than its height suggests.

(For contrast: we also checked the marine-weather projects `weather-mcp/weather-mcp`, `lucasinocencio1/mcp-surf-forecast` and the race-management project `sailing416/PRO-Regatta` — none of them had public discussion threads with content to draw on.)

---

## How to update this briefing

If the duty officer re-runs the feed and gets wave/wind numbers for Saturday through Monday, edit this file on the `week-2026-10-19` branch and push — the head coach reviews the pull request before anything counts.
