# Privacy-Checklist
A freely available toolkit for thwarting and subverting the data-whoring practices of big-tech.
These guides are intended for people attempting to escape "Hacker Hell", a situation in which all of their tech is 100% compromised.

I am not a cyber-security professional, just someone who had to tunnel their way out of this hell, and who has realized there's no guide for it. This is just a blueprint and ideally, I would like to see the slack picked up by an actual cyber-security expert.

-----------------------------------------

## IF YOU HAVE THE RESOURCES: CONTACT A PROFESSIONAL INSTEAD
## IF YOU HAVE TRANSPORTATION: SEEK AUTHORITIES INSTEAD
## Always remember to do your due-diligence, especially if you are unable to verify the integrity of your internet connection.

One should lock down their devices as-per the "https://github.com/TernaryFortress/Security-Checklist" repository prior to taking these steps.

I am not a security researcher, this is a blueprint assembled exclusively for, and detailing what is required to escape the aforementioned situation and establish contact with the outside world, in order to escape oppression and cyber-abuse. Other guides will provide more extensive and complete guidance, along with all the information-overload that such guidance entails.

# Understanding/Domain Knowledge
Man-in-the-Middle (MitM) - A tactic in which an adversary attempts place themselves in a position to directly alter your web-traffic.

Stingray - A form of MitM in which an attacker pretends to be a person or node on your network. Examples might include a fake cell tower or router, a compromised software uploader, or any other type of "gatekeeper".

Triangulation - A tactic in which an adversary attempts to learn your IP address so that they can MitM your connection. Telemetry is a common exfiltration vector of this information.

Cross-Site Scripting (XSS) - A tactic in which an adversary attempts to exploit poor sanitation of user content in a web application in order to execute arbitrary code.

Supply-Chain Attack - A tactic in which an adversary attempts to alter the software or data at the point-of-upload. Any downloads of the software will be tainted.



# Goal:
Be completely anonymous online.

# Encrypted Messaging
Use encrypted messengers whenever, wherever, and however you can.
Examples include: Signal, Element, etc.
Ensure that if you're using android, to properly lock down the common attack vectors as per our Security-Checklist prior to engaging in any of this, or you could lose your account.
Facebook has been known to cooperate with authorities - You may view this as a positive or a negative, depending on who's in charge at the time.

## Facebook 
Facebook sells your data. You will likely never be private using messenger, but here's how to lock down telemetry in the Facebook app (scroll right to see each step's full instruction set):
```
1: > "Settings & Privacy" or Gear Icon
2: > Settings & Privacy has a search box, begin typing "Your Activity off Meta Technologies", until you're able to select it as an option.
3: > Click "Manage Future Activity"
4: > Select "Disconnect Future Activity" and save.
5: > You should now see "Your off-Meta activity is currently turned off.", meaning that you're finished here.
6: > You should now be in accounts center, but if you're not you can use the search menu to fill in the gaps.
7: > Under "Password & Security", Add a 2-factor authentiction method: A security key is best if you have one, or if you're willing to purchase one. We recommend a thumbprint enabled one for more security.
8: > Go to "Ad Preferences", and select the "Manage info" tab at the top of the page.
9: > We want to have zero targeted ads. Go ahead and disable basically everything here. "Categories used to reach you", "Activity information from ad partners", "Ads shown outside of Meta", and "Social Interactions" should all be disabled/turned off to the maximum degree possible.
10: > Finally, "Audience-based advertising" includes every company that Facebook sells your data to. You should go into each advertiser, and select the "They uploaded or used a list to reach you" box in order to disable their access. For every single company in the list. Yeah, we know, but at least after that you're done.
```

## Messenger
In Facebook Messenger:
```
1: > "Settings & Privacy" or Gear Icon
2: > "Active Status" = Disabled
3: > "App lock" = Enabled
```
