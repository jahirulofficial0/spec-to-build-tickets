# Example

## Input

I want customers of my ISP to see their bill and pay online through bKash from a mobile web page.

## Output (abridged)

## Non-goals
- No plan upgrades/downgrades in v1

### T-3 Initiate bKash payment
Acceptance criteria:
- [ ] Given an unpaid invoice, When the user taps Pay, Then a bKash checkout is created with the exact due amount
- [ ] Given a duplicate callback, Then the invoice is marked paid only once (idempotent)
