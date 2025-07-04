STADI Web App Master Prompt
STADI is the ultimate fan ecosystem, blending rideshare, access control, ticket trading, drops, community, food concierge, and Web3 rewards into a seamless platform. This master prompt consolidates the vision, architecture, and features for the STADI web app, designed for growth, monetization, and fan engagement. Below is the complete feature map, page structure, and technical considerations for the MVP and scalable future phases.
🧩 App Overview
STADI combines event discovery, social coordination, ticket trading, exclusive rewards, and venue services into one platform. It’s a fan-first movement, integrating Web2 convenience with Web3 potential (tokens, NFTs, decentralized rewards). The app targets fans, group leaders, creators, and vendors, with monetization via ticket trading fees, premium memberships, and token-based redemptions.

🏟️ Page & Feature Architecture
🔱 1. Landing Page (Public)
Purpose: Hype fans, drive sign-ups, and showcase STADI’s value.Sections:

Hero: “Your Fan Life. Upgraded.” (CTA: Join Waitlist / Get Started)
How It Works: Simple explainer of booking, riding, perks.
Video Demo: Motion mockup or app walkthrough.
Upcoming Events / Hot Drops: Highlight trending events or rewards.
Token/Reward Explainer: Optional for MVP, teases Web3 perks.
Testimonials / Fan Feed: Social proof from users.
Footer: Links, socials, FAQ.

👤 2. User Onboarding / Signup
Purpose: Lightweight, verified signup with user type selection.Options:

Sign Up: Email, Google, Apple, Wallet (Phase 2).
User Types:
Fan
Group Leader / Organizer
Creator / Brand
Vendor / Driver (Future)


Profile Creation: Name, photo, favorite teams/artists/cities, mobile number (for SMS confirmations).

🏠 3. Home Dashboard
Purpose: Fan control center for events, rides, passes, and rewards.Features:

Upcoming Events
Active Passes
Today’s Drops / Claimables
Current Rides / STADI Pods
STADI Points (XP/token balance)
Invite Friends (referral rewards)

📍 4. Event Explorer
Purpose: Discover events (sports, music, festivals) by location or preferences.Filters:

Location, Date, Team/Artist, Type (Sports, Music, Culture), STADI Perks Available.Event Cards:
Event image, description, STADI rewards/tokens, “Join Event” CTA.

🗓️ 5. Event Detail Page
Purpose: Central hub for event info, rides, drops, and food orders.Sections:

Event info (date, venue, performer)
Join/Create STADI Pod (rideshare/crew)
View Pod mates
DropZone (view/claim exclusive items)
Interactive Map (parking, gates, meetups)
Food Concierge (order food/drinks)
Perks unlockable with STADI tokens

🚗 6. Ride Pod Page (STADI Pods)
Purpose: Social ride coordination for group experiences.Features:

Join or create a Pod
Set pick-up/drop-off locations
Pod chat
Payment splitting / STADI token rewards
Invite link (social or SMS)
Ride history and driver rating

🎟️ 7. Pass Vault
Purpose: Store digital tickets, fan credentials, and upgrades.Tabs:

Event Passes (QR scan + blockchain timestamp)
Fan ID (NFT, optional)
Upgrades / VIP Add-ons
Unlockables / Drops
Purchase History

🎟️ 8. Ticket Marketplace (Buy, Sell, Trade)
Purpose: Peer-to-peer ticket trading with Web3 support.Features:

Buy tickets (official partners + P2P)
List tickets for sale/trade
Filters: Section, price, verified fan
Secure transactions (Stripe, USDC, STADI token)
NFT ticket minting (on-chain proof of attendance)
Transfer ownership (wallet-to-wallet or user-to-user)
Dynamic pricing / live market feedPage Structure:
Event selector (calendar + search)
Ticket listings (filters, grid view)
Ticket detail modal (seat info, price history, seller stats)
Trade request flow (barter + upgrades)
“Post a Ticket” form

🎁 9. DropZone (Live & Upcoming Perks)
Purpose: Exclusive content, merch, NFTs, and token-based claims.Features:

Timed drops (NFTs, merch, rewards)
Secret location unlocks
QR scan to claim
Claim with STADI Points
Leaderboards (top fans / early claimers)

🛍️ 10. STADI Rewards Marketplace
Purpose: Redeem points/tokens for merch, upgrades, and perks.Redeemables:

Merch (exclusive, signed)
Event upgrades (VIP, fast pass, backstage)
Food/drink vouchers
Digital collectibles (NFT badges, tickets)
Ride credits or concierge perks
STADI Premium membershipCurrency:
STADI Points (earned via check-ins, referrals, purchases)
STADI Token (Phase 2, tradable ERC-20/SPL)Page Structure:
Marketplace home (showcase carousel)
Filters: Item type, price, newest, expiring soon
Item detail popup (redeem, gift, save)
Points balance & wallet preview

🍔 11. Food & Venue Concierge System
Purpose: Order food, skip lines, or get seat delivery.Features:

Browse menu by venue/event section
Order ahead for express pickup
Seat delivery (partnered stadiums)
Loyalty stamps (buy X, get Y)
Pre-event meal scheduling
STADI Pay (tokens, points, or card)Page Structure:
“Venue Eats” tab on event pages
Vendor carousel (e.g., Chickie’s, BBQ, beer garden)
Item detail modal (calories, price, wait time)
Add-to-order cart flow
Seat location auto-fill for delivery
Order history + quick reorders

💬 12. FanZone / Crew Chat
Purpose: Community threads for events, teams, or pods.Features:

Text / media sharing
Event-specific group chats
Verified Fan Clubs or Brand Threads
STADI bot drops rewards (“First to reply gets VIP!”)

🔐 13. User Profile
Purpose: Showcase fan stats, achievements, and fandoms.Tabs:

Stats (events attended, drops claimed, miles traveled)
Favorite Teams / Artists / Cities
Badges Earned
Wallet (token balance, earnings, redemptions)

🔗 14. Wallet (Phase 2 – Blockchain)
Purpose: Manage on-chain rewards, tickets, and earnings.Features:

STADI token balance
Connected Wallets (MetaMask, WalletConnect)
NFT Passes (Fan Pass, Event Badges)
Token transaction history
Transfer / redeem tokens

🛠️ 15. Admin / Organizer Dashboard (Optional MVP)
Purpose: Tools for artists, teams, or event hosts.Capabilities:

Post Events / Set Rewards
Manage Drops
Message Crews / Pods
Review Insights (engagement, attendance, wallet stats)
Airdrop rewards / tokens

🧾 16. Settings & Support
Features:

Profile preferences
Notifications
Privacy settings
Contact support / chat
Terms of service
Log out


💡 Future Pages (Post-MVP)

STADI DAO Voting Center: Fans vote on drop themes, VIP perks.
Creator Studio: Influencers post events and Pod invites.
STADI Experiences: Book concierge packages for premium fans.


🎯 MVP Roadmap

Landing Page
Onboarding + Home Dashboard
Event Explorer + Detail Page
STADI Pods
Pass Vault
Ticket Marketplace
DropZone
STADI Rewards Marketplace
Food Concierge
Profile + FanZone (light chat)
Rewards / Token Preview


⚙️ Technical Considerations
Ticket Marketplace

Web2: Stripe + SeatGeek/Ticketmaster API for official listings.
Web3: NFT tickets (ERC-721A or EIP-5555 for events). Smart contract for transfers + royalties.

Rewards Marketplace

Internal ledger for STADI Points.
Smart contract for token redemptions.
Admin dashboard for redeemables, stock, and limits.

Food Concierge

POS integration (Square, Clover, Toast).
QR check-in for vendors.
Live delivery via venue staff or 3rd-party ops.

Tech Stack

Frontend: React, JSX, Vite, Tailwind CSS (CDN: cdn.jsdelivr.net).
Backend: Node.js, Express, Firebase/PostgreSQL for user data.
Web3: base/Solana for tokens/NFTs, MetaMask/WalletConnect integration.
APIs: Stripe, SeatGeek/Ticketmaster, Square/Toast for POS.


👇 Next Steps

Draft UI/UX wireframes for new features (Ticket Marketplace, Rewards, Food Concierge).
Write technical specs (smart contracts, APIs, DB schemas).
Create a pitch deck for investors.
Break into milestones (MVP → Beta → Public).

STADI is a movement. Let’s build the ultimate fan ecosystem. 🚀

