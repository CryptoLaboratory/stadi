STADI User Flow
This document outlines the complete user flow for the STADI web app, from landing to logout, designed for an intuitive, app-like experience with a bottom navigation bar. STADI integrates event discovery, ticket trading, rideshare pods, rewards, food concierge, and community features.
1. Landing Page (Public)

Entry: User arrives at stadi.app via marketing, socials, or search.
View: Hero (“Your Fan Life. Upgraded.”), demo video, upcoming events, drops, testimonials, footer (links, socials, FAQ).
Action: Clicks “Join Waitlist” or “Get Started” to sign up.
Nav: Bottom nav (mobile) shows Home (active), Events, Pods, Marketplace, Profile.

2. User Onboarding / Signup

Sign Up: Email, Google, Apple, or Wallet (Phase 2).
User Type: Fan, Group Leader, Creator, Vendor (future).
Profile Creation:
Name, photo (optional).
Favorite teams, artists, cities.
Mobile number (SMS confirmations).


Outcome: Redirects to Home Dashboard.
Nav: Profile icon highlights briefly.

3. Home Dashboard

View: Upcoming events, active passes, rides/pods, drops, STADI Points, referral invites.
Actions:
Event card → Event Explorer/Detail.
Invite Friends → Shares referral link.
Drop → DropZone.
Ride/Pod → Ride Pod Page.


Nav: Home icon active.

4. Event Explorer

Browse: Filters by location, date, team/artist, type, STADI perks.
Action: Clicks event card → Event Detail Page.
Nav: Events icon active.

5. Event Detail Page

View: Event info, map, Pods, DropZone, “Venue Eats” (Food Concierge).
Actions:
Joins/creates Pod → Ride Pod Page.
Claims drop → DropZone.
Orders food → Food Concierge.
Views tickets/perks → Pass Vault.


Nav: Events icon active.

6. Ticket Marketplace

Browse: Filters tickets by section, price, verified fan.
Actions:
Buys ticket (Stripe, USDC, STADI token).
Lists ticket for sale/trade.
Views ticket details (seat, price history, seller stats).
Initiates trade request.
Mints NFT ticket (Phase 2).


Outcome: Tickets appear in Pass Vault.
Nav: Marketplace icon active.

7. STADI Pods

Join/Create: Sets pick-up/drop-off locations.
Actions:
Chats in Pod thread.
Splits payment.
Shares invite link.
Rates driver.


Outcome: Ride history saved; points earned.
Nav: Pods icon active.

8. Rewards Marketplace

Browse: Merch, upgrades, vouchers, NFTs, ride credits.
Filters: Item type, price, newest, expiring soon.
Actions:
Redeems with points/tokens.
Gifts or saves item.


Outcome: Items in Pass Vault/Profile.
Nav: Marketplace icon active.

9. Food Concierge

Access: From Event Detail (“Venue Eats”) or direct link.
Browse: Menu by venue/section.
Actions:
Orders for pickup/delivery.
Schedules pre-event meal.
Pays with STADI Pay.
Earns loyalty stamps.


Outcome: Order history saved; points earned.
Nav: Events or Marketplace icon.

10. FanZone Chat

Access: From Event Detail, Pods, or FanZone link.
Engage: Joins event/team/Pod chats; shares text/media.
Actions: Claims STADI bot rewards.
Outcome: Points for engagement.
Nav: Pods or Events icon.

11. Pass Vault

View: Event Passes, Fan ID (NFT), Upgrades, Unlockables, Purchase History.
Actions:
Scans QR for entry.
Views/redeems upgrades/drops.


Nav: Profile icon (or future Vault icon).

12. User Profile

View: Stats, favorites, badges, wallet balance.
Actions:
Edits profile.
Shares stats.


Nav: Profile icon active.

13. Wallet (Phase 2)

View: Token balance, connected wallets, NFT passes, transaction history.
Actions:
Transfers tokens/NFTs.
Redeems tokens.


Nav: Profile icon (or future Wallet icon).

14. Settings & Support

Actions:
Updates preferences, notifications, privacy.
Contacts support.
Reviews terms.
Logs out.


Nav: Profile icon active.

15. Logout

Action: Clicks “Log Out” in Settings.
Outcome: Returns to Landing Page; session cleared.

Notes

Bottom Nav: Fixed on mobile (Home, Events, Pods, Marketplace, Profile); sidebar/top nav on desktop.
Tech: React, Vite, Tailwind CSS, react-router-dom for routing.
Web3: Optional NFT/token integration (Phase 2).
Engagement: Drops, points, and leaderboards drive interaction.
Accessibility: ARIA labels, keyboard navigation support.
