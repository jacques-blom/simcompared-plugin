---
name: find-an-esim
description: "Find a travel eSIM that fits a destination, trip length, data allowance or feature request. Use when someone asks for a cheap plan, a weekly or monthly option, unlimited data or hotspot access."
---

# Find an eSIM

1. If the place is ambiguous, call `search_destinations` and choose the matching country or region. Ask for trip days or data only if the answer depends on details the traveller has not given.
2. Call `compare_plans` with the destination, total days, and minimum total GB or `"unlimited"`. Use the traveller’s preferred published currency and request hotspot or a phone number only when needed.
3. Lead with the matching offer. Give its data, validity, published currency and date. Keep local SIMs and area-only offers separate. Explain the cost or fit of any alternative using the returned facts.
4. Cite the human `url`. Use the signed `go_url` for opening the provider, and place the result’s `disclosure` line beside provider links. When no offer fits, say which requirement was unmet and ask before relaxing it.

Check `phone_esim_support` with the exact model and purchase region if device support matters. Use the manufacturer observation’s scope to qualify the answer.
