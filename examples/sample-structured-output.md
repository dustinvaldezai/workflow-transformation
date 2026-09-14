# Synthetic Structured Output

This is an illustrative structured result derived only from [`sample-source.md`](./sample-source.md). It is hand-authored for demonstration and is not a recorded model run.

## Extracted claims

| ID | Claim | Source | Qualification |
| --- | --- | --- | --- |
| C1 | A beginner digital-skills workshop is proposed. | S1 | Proposed, not confirmed. |
| C2 | Registration instructions should use plain language. | S1 | No tested instructions supplied. |
| C3 | The meeting room is reported available Thursday evening. | S2 | Availability is not the same as a confirmed booking. |
| C4 | Wi-Fi is reported available. | S2 | Suitability or bandwidth is not stated. |
| C5 | Loaner laptops are not provided. | S2 | Other device support is not stated. |
| C6 | The facilitator is available Tuesday but unavailable Thursday. | S3 | Alternate room availability is unknown. |
| C7 | A bring-your-own-device format may create an access barrier. | S3 | This is a concern, not measured participant demand. |

## Themes

- **Scheduling:** C3, C6
- **Access and communication:** C2, C5, C7
- **Scope and infrastructure:** C1, C4

## Conflict requiring validation

The room is available Thursday, while the facilitator is unavailable Thursday. The workflow should not treat Thursday as confirmed.

## Open questions

- Is the room available Tuesday?
- Is another facilitator available Thursday?
- What device support can be offered?
- Is the Wi-Fi suitable for the planned workshop?
- What accessibility requirements should be considered?

## Draft synthesis

The available notes support continuing workshop planning, but they do not support confirming Thursday. The team should resolve the room and facilitator scheduling conflict, clarify device support and Wi-Fi suitability, and prepare plain-language registration instructions.

## Human-review status

**Pending.** A reviewer should verify that no unsupported date, attendance, device-demand, or accessibility claims have been introduced before this becomes decision-ready.
