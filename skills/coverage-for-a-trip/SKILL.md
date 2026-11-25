---
name: coverage-for-a-trip
description: "Find one eSIM that covers a multi-country trip, or compare regulator-modelled outdoor mobile networks for a place or route."
---

# Coverage for a trip

1. For several countries, call `route_plans` with every stop, total days, and minimum total `data_gb` or `"unlimited"`. Compare only plans that cover all stops and meet the trip needs. Cite the human route page and say when the result points to the route directory.
2. For a route or place with a signal question, call `coverage` with the country and place, such as Australia and Great Ocean Road. Use the requested technology or speed tier. Quote the modelled outdoor percentage and gaps as returned.
3. For a plan using that network, only name offers that list it. Separate plan validity from the coverage model. Cite the coverage page, and use the signed `go_url` and the returned `disclosure` line next to provider links.
