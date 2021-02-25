# RaiderioTop100
Scrapes player data for top players 100 from various categories
current order is: top 100 overall, top 100 role, top 100 for each spec

current issues:
1) Probably need to add an expected conditions for next page buttons because it can cause errors when the page lags.
2) Opening a new browser for the spec pages is a fix for a stale element/DOM issue with spec pages. The solution could be improved, but it works just fine.
3) Concurrency should be looked into because the program takes awhile to execute currently. However, there would be issues with becoming locked due to ddos protection if requesting too frequently.


