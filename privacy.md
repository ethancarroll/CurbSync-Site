# Privacy Policy

**CurbSync**  
**Last updated: May 25, 2026**

## Overview

CurbSync ("we", "our", "the app") helps you time airport trips by tracking flight status and drive times — whether you're catching a flight or picking someone up. This policy explains what data we collect, how we use it, and your rights.

## Data We Collect

### Account Information

When you sign in with Apple, we receive:
- A unique Apple user identifier (opaque ID)
- Your name and email (only if you choose to share them)

We do not receive or store your Apple ID password.

### Flight Information

- Flight numbers you choose to track
- Airport codes you select

This data is used solely to fetch arrival status and is deleted when you remove a tracked flight.

### Location and Address Data

With your permission, CurbSync uses your device's location to determine your starting point. The location is reverse-geocoded **on your device** into a human-readable address (e.g. "123 Main St, Springfield, IL"). You may also enter or override this address manually.

The resulting address is sent to our server only when you start tracking a flight, so we can store the tracking record. Raw GPS coordinates are never sent to our server.

**Drive times are calculated entirely on your device** using Apple Maps (MapKit). Your origin and destination are not sent to any third-party routing service.

### Device Tokens

- Apple Push Notification Service (APNs) device tokens for sending flight update notifications
- Live Activity push tokens (Pro subscribers)

These tokens are stored on our server and deleted when you sign out or delete your account.

### Subscription Information

- Your subscription tier (Free or Pro)
- App Store transaction identifiers for receipt verification

We do not have access to your payment method or billing details. All purchases are processed by Apple.

### Usage Data

- Aggregate API request counts for rate limiting (Free tier: 20 requests/day)

We do not track your browsing habits, app usage patterns, or analytics beyond rate limiting.

## How We Use Your Data

- Flight tracking: Fetch real-time arrival/departure data from FlightAware AeroAPI
- Drive time: Calculated **on your device** via Apple Maps; no data sent to our server for this
- Notifications: Send push notifications when it's time to leave (Pro)
- Rate limiting: Enforce free-tier usage limits
- Account management: Authenticate your identity and manage your subscription

## Third-Party Services

We use the following services to operate CurbSync:

- Apple (Sign in with Apple): https://www.apple.com/privacy/
- FlightAware AeroAPI: https://www.flightaware.com/about/privacy/
- Apple Push Notification Service: https://www.apple.com/privacy/

Drive-time calculation uses Apple Maps locally on your device and does not transmit data to any third party.

We do not sell, rent, or share your personal data with advertisers or data brokers.

## Data Retention

- Account data: Retained until you delete your account
- Tracked flights: Retained on our server until you remove them, your flight is marked completed (typically within hours of arrival), or the record is older than 48 hours with no activity
- Device tokens: Retained until you sign out or delete your account

## Your Rights

You can at any time:
- Delete your account and all associated data from Settings -> Delete Account
- Sign out to remove your local session
- Stop notifications by revoking notification permissions in iOS Settings

Upon account deletion, all your data is permanently removed from our servers.

## Children's Privacy

CurbSync is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy from time to time. Material changes will be communicated through the app. Continued use after changes constitutes acceptance.

## Contact

If you have questions about this privacy policy, contact us at:

- Email: support@curbsync.app
