# Privacy Policy - Curv

Last updated: May 20, 2026

Curv is a motorcycle route planning and navigation app that helps generate round trips and point-to-point routes, save route history, export GPX files, and discover public routes nearby. This policy explains what data the app processes and how.

## 1. What data we process

### Account and app protection

Curv uses Firebase Authentication to create guest sessions and, if you choose, registered accounts using email/password or Google sign-in. Firebase may process your Firebase user ID, email address, display name, authentication tokens, and sign-in metadata.

Curv stores your Firebase user ID, account type, email address and display name when available, account status, premium tier, last-seen time, app version, user agent, and a hashed version of your IP address for account, quota, security, and abuse-prevention purposes. We do not store raw IP addresses in the Curv database.

Curv also uses Firebase App Check to verify that requests come from a genuine app build. App Check may use platform integrity services such as Play Integrity, App Attest, or DeviceCheck.

Firebase privacy information is available at:
https://firebase.google.com/support/privacy

### Location and place search

When you type a starting location, destination, or waypoint, the search text is sent to the Curv server to convert it into coordinates. Curv uses its own geocoding service first. If needed, the server may fall back to OpenStreetMap Nominatim. In that fallback case, Nominatim receives the search text as a server-side request from Curv, not directly from the app.

Search text is not stored as a standalone search log. If you generate and save a route, the route name, route points, and coordinates may be stored as part of your route history.

OpenStreetMap/Nominatim policy information is available at:
https://operations.osmfoundation.org/policies/nominatim/

### Device location

If you allow location access, Curv uses your current location to show your position on the map, follow your route during navigation, and find public community routes near you. During active navigation, location updates are processed in the app to calculate progress and guidance.

When you search for nearby public routes, your current coordinates are sent to the Curv server for that request.

Curv does not store continuous live navigation location history. However, precise coordinates may be stored when they are part of saved routes, exported routes, shared routes, or published public routes.

### Route generation and preferences

Your route coordinates, route distance, curve preference, highway preference, destination, and waypoints are sent to the Curv server to generate routes. Routing is handled by Curv’s routing server.

Curv stores compact weekly usage counters for route generation, geocoding, and GPX exports.

Generated routes are saved to your Curv route history. Saved route data may include route coordinates, start location, route points, instructions, distance, duration, curve count, creation time, and route name. Private route history is kept for your account and older private routes may be pruned automatically.

If you publish a route, it becomes visible to other Curv users through community routes and share links.

### Community routes, sharing, and likes

If you publish a route, Curv stores and displays that route as public. Public routes may include the route path, start area, route summary, share code, publication time, and like count.

If you like a public route, Curv stores that like so it can show your liked routes and update the public like count.

### Map display

Curv’s current map renderer uses MapLibre with OpenFreeMap map styles and tiles by default. OpenFreeMap receives standard HTTPS request information such as your IP address and requested map style/tile resources, which can reveal an approximate map viewport.

Some legacy or fallback builds may request raster map tiles through the Curv server. In that mode, Curv receives the requested tile coordinates and standard request metadata, then fetches map tiles from the configured tile provider.

OpenFreeMap privacy information is available at:
https://openfreemap.org/privacy/

### Premium subscriptions

Curv uses RevenueCat to manage Premium subscriptions and entitlement status. Curv sends your Curv/Firebase user identifier to RevenueCat to check whether Premium is active.

RevenueCat, Apple, and Google may process purchase and subscription information, including purchase history, subscription status, renewal status, and store receipt information, according to their own policies. Curv does not store your payment card details.

RevenueCat privacy information is available at:
https://www.revenuecat.com/privacy/

### GPX export

When you export a route, Curv sends the route coordinates and route name to the Curv server to generate the GPX content and count the export for quota purposes. The app then writes the GPX file to your device cache and opens your device’s share sheet. What happens after you share the file is governed by the app or service you share it to.

## 2. App Store privacy summary

For App Store privacy purposes, Curv may collect the following data linked to your account or app user identity:

- Email address, if you create an account
- User ID, including Firebase or Curv account identifiers
- Purchase history, through RevenueCat, Apple, or Google subscription processing
- Precise location, when coordinates are used for route generation, nearby route search, saved routes, exported routes, shared routes, or published routes

Curv uses this data for app functionality, account management, subscription access, route generation, saved route history, security, quota enforcement, abuse prevention, and limited service analytics.

Curv does not use this data for third-party advertising or tracking across apps and websites.

## 3. What data we do not collect

- We do not use advertising SDKs
- We do not sell or rent your personal data
- We do not store raw IP addresses in the Curv database
- We do not collect contacts, photos, payment card numbers, or phone numbers
- We do not store continuous navigation location history, except where coordinates are part of saved, exported, shared, or published routes

## 4. Data storage and retention

Curv stores account, quota, route history, public route, and like data on Curv servers. Private saved route history may be automatically limited to the most recent routes. Public routes remain available while they are published. GPX files written by the app are stored in your device cache and are managed by your operating system.

Curv may retain limited records where needed for security, abuse prevention, operational, legal, or billing-related reasons.

## 5. Account deletion and your choices

You can delete your Curv account from the app. Deleting your account removes your Firebase sign-in account and signs you out of Curv.

Deleting your Curv account does not automatically cancel a Google Play or Apple subscription. You must cancel subscriptions through the store where you purchased them.

You can also control location access through your device settings. If location access is disabled, some map, navigation, route generation, and nearby route features may not work correctly.

For questions, deletion requests, or requests about server-side account or route data, contact us at the address below.

## 6. Children’s privacy

Curv is not directed at children under 13. We do not knowingly collect personal information from children.

## 7. Changes to this policy

We may update this policy when the app’s functionality changes. When we do, we will update the date at the top of this page. Continued use of the app after changes constitutes acceptance of the updated policy.

## 8. Contact

If you have questions about this policy, you can contact us at:

braxxtech@gmail.com
