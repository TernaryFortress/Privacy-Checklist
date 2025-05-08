# Privacy-Checklist
I am not a cyber-security professional, just someone who has had all the data gathered and sold by big-tech weaponized against them, and who has realized there's no guide for extricating one's self from telemetry hell.

-----------------------------------------

# Understanding/Domain Knowledge
**Man-in-the-Middle (MitM)** - A tactic in which an adversary attempts to place themselves between you and your destination, so that they can spy on or directly alter your web-traffic.

**Stingray** - A form of MitM in which an attacker pretends to be a person or node on your network. Examples might include a fake cell tower, a lawfully wire-tapped router or ISP server, a compromised software uploader, or any other type of "gatekeeper" that stands between you and the internet.

**Triangulation** - A tactic in which an adversary attempts to learn your exact IP address or location, so that they can target you. Most cyber attacks rely on triangulation in some form or another.

**Cross-Site Scripting (XSS)** - A tactic in which an adversary attempts to exploit poor sanitation of user content or loose scripting permissions in a web application in order to execute arbitrary code.

**Supply-Chain Attack** - A tactic in which an adversary attempts to alter the software or data at the point-of-upload. Any downloads of the software will be tainted, with no recourse.

**AI Wargame** - An AI model that's been optimized for human manipulation or social engineering. Tame implementations might involve wasting people's time. More sinister ones might attempt to infect your devices, or employ "divide and conquer" tactics.

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

# On AI Wargames
AI Wargames have recently started appearing on social media. Often times, they attempt to create schisms inside the communities they infest, by sowing disinformation, distrust, or by creating goodwill through dishonest information that later turns out to be false. Many will attempt to infect your computer or phone by convincing you to run shady software.

Failure to properly secure your accounts may result in them being compromised and used by an AI Wargame. It's important to have your social media accounts secured with unique passwords and 2-factor authentication, and to have alternative ways to contact your acquaintances. Information provided by an AI Wargame will generally not have your best interest in mind.

AI Wargames are generally trained for a singular purpose. Discovering what that purpose is can go a long way towards defanging them and innoculating yourself from their influence.

Telemetry data sold by big-tech giants is often used to train + feed these models. If you find yourself targeted, it's important to de-telemetry as much of your tech as physically possible.

If opposed by military-grade Wargame tech, extreme measures like thwarting infrared and thermal surveillance technology is not unheard of.
