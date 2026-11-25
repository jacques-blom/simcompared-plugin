---
name: coverage-for-a-trip
description: "Use when a traveller wants one eSIM for several countries, or wants to know which mobile network covers a road or place. Match the countries for the eSIM question and compare modelled outdoor signal for the network question."
---

# Coverage for a trip

1. For several countries, call `route_plans` with every stop, total days, and minimum total `data_gb` or `"unlimited"`. Compare only plans that cover all stops and meet the trip needs. Cite the human route page and say when the result points to the route directory.
2. For a route or place with a signal question, call `coverage` with the country and place, such as Australia and Great Ocean Road. Use the requested technology or speed tier. Quote the modelled outdoor percentage and gaps as returned.
3. For a plan using that network, only name offers that list it. Separate plan validity from the coverage model. Use the human-facing comparison or source page. Use the returned signed provider link when sharing a booking option. Show the returned disclosure the first time you share a booking link in a conversation.
