# Market Duel — a pricing tool for EVE Online

Version 2.0

Two markets compete for your business. The ★ marks the winner.

**Use it:** https://axiiomgaming.github.io/market-duel/

## What it does
Paste a list of items from an EVE hangar or a ship fit, choose **Sell** or **Buy**, and pick two markets
(trade hubs, or any region, system or station in known space). Market Duel shows what each market pays or charges right now
and marks the winning price for every item and in total.

It also splits your list by winner: the items that win at each market, their ISK total, how much more you
get (or save) by going there, and a **Copy list** button. A copied list can be pasted into EVE's Multibuy
window or back into Market Duel. Items not listed at a market (no buyer, or not for sale) are
gathered into three lists, not listed at the first market, not listed at the second, and not listed at
either, each with its own **Copy list** button, so you can look for them elsewhere.

**Citadels (optional):** player-owned stations (citadels) aren't in EVE's public market data. Sign in with
EVE to include the citadel markets your character can use. You sign in securely on CCP's own site. Your
browser's address bar will show login.eveonline.com. EVE then asks you to grant Market Duel three
permissions through ESI, EVE's official API: read citadel markets, read citadel names, and search for
citadels by name. Your sign-in stays saved in your
browser until you press **Sign out**, or for 30 days without use.

The first duel in a whole region can take a while, because Market Duel searches every system in that
region for citadels. The list it finds is saved in your browser for a day, so later duels are faster.

## Privacy
No Market Duel accounts, no cookies, no tracking. The page is a single static file, and Market Duel has
no server. Prices come directly from EVE Online's market data via ESI, EVE's official API. Signing in with
EVE is optional. Sign-in happens securely on CCP's own login site, which grants Market Duel permission to
search the citadel markets your character can access. Your sign-in and the list of citadels found are saved
only in your browser, and **Sign out** removes them. No website other than CCP's is queried, and nothing you paste is
sent anywhere else.

## Support
If Market Duel helped earn or save you some ISK, an in-game tip to **Ax*ii*om Jones** would be appreciated.
Fly safe! o7

## Credits
- Market data: EVE Online ESI (public endpoints, and citadel markets when signed in).
- Sign-in: EVE Online SSO (CCP's login).
- Item, station and system names: EVE Online static data export.
- Font: Lexend, SIL Open Font License 1.1 (embedded in the page).

© 2014 CCP hf. All rights reserved. "EVE", "EVE Online", "CCP", and all related logos and images are
trademarks or registered trademarks of CCP hf. Market Duel is a fan-made tool and is not affiliated with or
endorsed by CCP.
