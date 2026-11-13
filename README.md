# Palo Alto Swim & Sport pool schedule — Pool Relay embed preview

A replica of [paloaltoswim.com/pool-schedule](https://paloaltoswim.com/pool-schedule/) (Rinconada Pool), with its
schedule images replaced by live [Pool Relay](https://www.poolrelay.com) calendars. Edit `src/`, then
`python3 build.py`.

| Page | Replaces | Calendars |
|---|---|---|
| `index.html` | `/pool-schedule/` | week `ug9U0ohAHtSo8259xlEyhf` · lane by lane `rFMdA1KaDOOAHVvK4VL2bb` |

Source: the Rinconada Pool Schedule PDF, Fall: September 8 – October 31, 2026, read 2026-10-08.

## Registration

Each page lists its pools' programs under "Register at …", filled live by `live.js` (`data-live="register"`) from each
group's Pool Relay passes: what it offers, its price range, and a link to its Pool Relay registration page.
