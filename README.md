# Client Enquiry Assistant — README

## What this is

When someone new (or someone who's contacted you before) fills out your
enquiry form, this system reads their message, checks whether they're
already in your CRM, and creates or updates the record for you. Most of the
time, that's it, one less thing you had to do by hand.

## How it works, day to day

1. A prospective or returning client fills out the enquiry form.
2. The system reads their message, checks whether they're already a
   contact, and creates or updates their record in Pipedrive automatically.
3. **Most of the time, nothing more happens.** The record is simply ready
   and waiting the next time you open Pipedrive, no action needed from you.
4. **Sometimes, you'll get a Slack message instead.** This happens when the
   system isn't confident enough to act on its own, or something needs a
   second pair of eyes before it touches your CRM.

## When you get a Slack message

Every flagged message tells you why it was flagged, in plain language, for
example:

> ⚠️ Low Confidence Score: The model could not confidently process this
> enquiry.

Along with the original message and a summary of what the system understood
from it, so you can compare the two at a glance without digging through
Pipedrive first.

**What to do:** read the reason, glance at the enquiry, and either correct
the record yourself in Pipedrive or confirm it looks fine. Nothing gets
written to your CRM from a flagged case without you looking at it first.

## What this system does not do

- It doesn't run your actual consulting work, schedule calls, or write
  proposals for you.
- It only handles the very first enquiry. Once a real conversation starts,
  a call, an ongoing project, you're working the way you always have, this
  system stays out of it entirely.
- It never messages a client on your behalf.

## Where to find things

- **New or updated leads:** your Pipedrive Leads Inbox, as usual.
- **Anything needing your attention:** the Slack channel this system posts
  to.
- **A summary of what the client actually said:** attached as a note on
  their Pipedrive record.

## If something looks wrong

If a record looks incorrect, or a Slack flag doesn't make sense, don't try
to fix the system yourself, just correct the record in Pipedrive as you
normally would, and let whoever maintains this system know so the underlying
issue can be looked at.
