# Privacy Policy — History After Dark Publisher

**Last updated: 21 July 2026**

History After Dark Publisher ("the App") is a personal content-publishing
tool. It generates short historical video content and publishes it to a
single TikTok account operated by the App's own developer.

## Who this policy covers

The App has one user: its developer, who is also the owner of the TikTok
account it publishes to. It is not offered to the public, has no user
sign-up, and does not process data belonging to any other person.

## What the App accesses

When the developer authorizes the App through TikTok's standard OAuth
flow, TikTok issues the App:

- An **access token** and **refresh token** for the authorized account
- The account's **open ID**, **display name**, and the **privacy level
  options** available to it, retrieved from TikTok's Creator Info endpoint
  immediately before each post

These are the only categories of data the App receives from TikTok. The
App requests two scopes:

- `user.info.basic` — to display the account name before posting, as
  required by TikTok's UX guidelines
- `video.publish` — to publish videos to the authorized account

## What the App does with it

Tokens and account identifiers are written to a single file on the
developer's own computer and used only to authenticate requests to
TikTok's Content Posting API. The account name and privacy options are
displayed in the terminal before a post so the developer can confirm the
destination account and choose a permitted privacy level.

## Where data is stored

All data stays on the developer's local machine. The App runs entirely
offline apart from its calls to TikTok's API. There is no server, no
database, no hosted backend, and no analytics or telemetry of any kind.

## What the App does not do

- It does not collect, store, or process data about any TikTok user other
  than the authorizing account holder
- It does not sell, share, rent, or transfer data to any third party
- It does not use data for advertising, profiling, or model training
- It does not read, scrape, or store other users' videos, comments,
  profiles, or messages

## Retention and deletion

Tokens are retained only while the App is in use. The developer can
revoke access at any time from TikTok's **Manage app permissions** page,
or by deleting the local token file, which immediately and permanently
ends the App's access. Revoking access through TikTok invalidates the
tokens server-side.

## Content disclosure

All video content published by the App is generated using AI tools. Every
post is submitted with TikTok's `is_aigc` flag set to true, so it carries
TikTok's "Creator labeled as AI-generated" label.

## Children's privacy

The App is not directed at children and processes no data about them.

## Changes to this policy

Any change to this policy will be published at this URL with an updated
revision date.

## Contact

Questions about this policy can be sent to: **[YOUR EMAIL HERE]**
