# Privacy-Checklist
I am not a cyber-security professional, just someone who has had all the data gathered and sold by big-tech weaponized against them, and who has realized there's no guide for extricating one's self from telemetry hell.

-----------------------------------------

# Understanding/Domain Knowledge
**Man-in-the-Middle (MitM)** - A tactic in which an adversary attempts to place themselves between you and your destination, so that they can spy on or directly alter your web-traffic.

**Stingray** - A form of MitM in which an attacker pretends to be a person or node on your network. Examples might include a fake cell tower, a lawfully wire-tapped router or ISP server, a compromised software uploader, or any other type of "gatekeeper" that stands between you and the internet.

**Triangulation** - A tactic in which an adversary attempts to learn your exact IP address or location, so that they can target you. Most cyber attacks rely on triangulation in some form or another.

**Cross-Site Scripting (XSS)** - A tactic in which an adversary attempts to exploit poor sanitation of user content or loose scripting permissions in a web application in order to execute arbitrary code.

**Supply-Chain Attack** - A tactic in which an adversary attempts to alter the software or data at the point-of-upload. Any downloads of the software will be tainted, with no recourse.

# Goal:
Be completely anonymous online.

# Encrypted Messaging
Use encrypted messengers whenever, wherever, and however you can.

Examples include: Signal, Element, etc.

Ensure that if you're using android, to properly lock down the common attack vectors as per our Security-Checklist prior to engaging in any of this, or you could lose your account.

# Thwarting Stingrays
Using Walled Gardens (Google Play Store, Microsoft Store, Snap for Linux, Apple Store, etc) is usually a safe way to download legitimate software without fear of interception, protecting from everything except Supply-Chain Attacks.

Diffie-Helmann Key Exchange (For example, using the Wireguard VPN protocol) can bypass stringrays, so long as the plaintext keys are protected during the initial transport.

Proton VPN and Cloudflare Warp/Cloudflare One Agent are all Wireguard based. Android appears to have backdoors through Cloudflare One currently.

Note: Be sure to upgrade your phones, computers, and router firmware using known-safe connections whenever able, as Wireguard protocols from before 2024 are not secure.

# Cross-Site Scripting (XSS)
If a website or application is vulnerable to cross-site scripting at the same time that an attacker is able to identify you as a unique user to that site, this is functionally a Supply-Chain-Attack on its own, and you may want to just find another website to serve your needs.
