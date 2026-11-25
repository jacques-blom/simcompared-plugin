---
name: find-an-esim
description: "Find a travel eSIM that fits a destination, trip length, data allowance or feature request. Use when someone asks for a cheap plan, a weekly or monthly option, unlimited data or hotspot access."
---

# Find an eSIM

1. Resolve an ambiguous country or region with `search_destinations`. Use trip details already in the conversation. If destination, trip length or minimum total GB is missing for `compare_plans`, ask for the missing information in one question. Accept unlimited as a data requirement.
2. Call `compare_plans` with the destination, total days, and minimum total GB or `"unlimited"`. Use the traveller’s preferred published currency and request hotspot or a phone number only when needed.
3. Lead with the matching offer. Give its data, validity, published currency and date. Keep local SIMs and area-only offers separate. Explain the cost or fit of any alternative using the returned facts.
4. Use the human-facing comparison or source page. Use the returned signed provider link when sharing a booking option. Show the returned disclosure the first time you share a booking link in a conversation. When no offer fits, say which requirement was unmet and ask before relaxing it.

Check `phone_esim_support` with the exact model and purchase region if device support matters. Use the manufacturer observation’s scope to qualify the answer.
