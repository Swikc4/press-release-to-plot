# MP03 Methodology — Team 11

## 1. Ticker-list rationale

For this project, our team used the seeded ticker lists that were already provided in the MP03 starter materials. We used the Financial Services ticker list for the Financial Services industry and the Travel and Hospitality ticker list for the Travel and Hospitality industry. We decided not to randomly add extra tickers because the seeded lists were part of the assignment setup, and using them keeps the project consistent and easier to reproduce.

One issue we found is that the seeded ticker lists were very narrow compared to the SEC search results. For Financial Services, the 360-day search returned 250 raw candidates, but only 1 candidate matched the seeded ticker list. For Travel and Hospitality, the 360-day search also returned 250 raw candidates, but only 3 candidates matched the seeded ticker list. This shows that the ticker lists may not include many companies that appear in the broader SEC search results.

## 2. Search-phrase rationale

New search phrases were added instead of using just the ones that were given. In total, each industry had 40 search phrases. This was to make sure that the search could find any events that matched the phrases and gave us a higher chance of finding them.

## 3. Window-experiment results

We tested the required time windows: 30, 60, 90, 180, and 360 days. The goal was to see whether both industries could reach at least 8 geocoded location events.

In our results, both industries did reach at least 8 events. At the 180 day window, Travel and Hospitality reached 11 events, and at the 30 day window, Financial Services reached 38 events.

## 4. Stage 3 classification quality per industry

Stage 3 was designed to be strict. It only counted a filing as a location event if the filing clearly announced an opening, closing, relocation, or expansion of a specific physical facility in a named location.

For Financial Services, out of all the findings, only 38 could be geocoded. For Travel and Hospitality, only 11 could be geocoded. This does not necessarily mean there were no real location changes in these industries. It means that the filings found by our pipeline did not clearly meet the project’s definition of a location event.

## 5. Limitations

The biggest limitation was trying to get geomarkers for our map. Without expanding the search phrases, we had no events that could be geocoded, and the one that we did could not go on the map.

## Attribution

Team 11: Swikriti KC (Financial Services Pipeline Lead), Imran Aslam (Travel and Hospitality Pipeline Lead), Gabriel Asimakopoulos (Comparison and Visualization Lead / Integrator).
