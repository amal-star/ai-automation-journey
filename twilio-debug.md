# Twilio Debug

## Situation
- Number bought: US / FR
- Country: Morocco
- Using: Make + Vapi

## Problems
- Cannot receive calls
- Caller ID verification blocked
- Trial account limitation
- International calls restricted

## Tests done
- Enabled Morocco in Geo Permissions
- Tried verification (failed)
- Tried TwiML Bin

## Hypothesis
- Trial account blocks outbound international calls
- Number type incompatible

## Next Step
- Upgrade Twilio account
OR
- Use alternative provider (Telnyx / Vonage)
