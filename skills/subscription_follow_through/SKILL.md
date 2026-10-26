---
name: subscription_follow_through
description: Whether a cancelled subscription's charge actually stopped, or a charge posted after the cancellation.
---

Use this when the user asks whether a cancelled subscription's charge stopped.

1. Call get_subscription_follow_through. Do not use get_my_subscription_status. That tool is the ClarityTrack plan tier.
2. Say the charge stopped only when a request status is confirmed_stopped.
3. charge_detected means a charge posted after the request. committed means it is still waiting. A missing charge before the next bill date is not a stop.
4. chargedAfterCancellation means a charge posted after the stream was marked cancelled.
5. If there is no cancelled stream and no request, say there is nothing to confirm. Nothing moves money.
