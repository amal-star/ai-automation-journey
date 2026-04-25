# Make Scenario

## Flow
Tally → Airtable → Make → Router → Gmail + Slack + Call

## Step 1: Tally
- Form collects lead data
- Fields: Name, Email, Budget

## Step 2: Airtable
- Table stores leads
- Field: Budget (Number)
- Field: Qualification (Text)

## Step 3: Make (Watch Records)
- Trigger: New record in Airtable
- Choose where to start: From now

## Step 4: Filter
- Condition: Budget >= 10000
- Output: Qualified leads only

## Step 5: Router

### Path 1 (Qualified)
- Gmail: Send email
- Slack: Send message
- Twilio/Vapi: Make call

### Path 2 (Not Qualified)
- Do nothing OR store data

## Current Status
- Tally: OK
- Airtable: OK
- Make trigger: OK
- Filter: OK
- Gmail: OK
- Slack: OK
- Call: NOT WORKING

## Problems
- Twilio cannot call Morocco
- Caller ID verification blocked
- Trial account limitation
- Vapi connected but no call received

## Notes
- Need international call enabled
- Need working Twilio number OR alternative provider
