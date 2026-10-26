---
name: duplicate_charges
description: List open charges that look like the same charge on two accounts.
---

Use this when the user asks whether the same charge shows on two accounts.

1. Call get_my_duplicate_charges.
2. List any open duplicate charges with the merchant and the amount.
3. If the list is empty, say there are no open duplicate charges.
4. Do not mark one intentional. That happens in ClarityTrack. Nothing moves money.
