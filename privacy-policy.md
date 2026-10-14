# Hivestorm Privacy Policy

*Last updated: 14 October 2026*

Hivestorm is an arcade shooter for iPhone, made by one person: Stian Andre Olsen. This policy explains what data the game handles and why.

**The short version**

- You can play without giving any personal information. There's no sign-up, no email address and no real name.
- The game has no ads, no tracking and no crash reporting, and adds no analytics of its own (section 5 covers what Unity does). Nothing is sold or shared for advertising.
- Online co-op and the online high scores use Unity Gaming Services with an anonymous, random player ID.
- The online high scores are opt-in. Nothing is posted until you choose a nickname. After that, the game stores your nickname, your best scores and the stage each one reached, and nothing else.
- **DELETE MY ONLINE DATA** in the game removes all of it, at any time.

## 1. Who is responsible

The controller under the EU General Data Protection Regulation (GDPR) is Stian Andre Olsen, an independent developer based in Norway.
Contact: **st-aolse@online.no**

## 2. Data that stays on your phone

The game saves the following on your device only. I can't see it, and it isn't sent anywhere:

- your settings (sound, music, haptics, frame rate)
- your ten best games per mode on this phone (score, stage, date, and "YOU" or your nickname)
- your nickname, if you chose one
- scores that are waiting to be posted, if you've joined the online high scores and were offline when a game ended
- for the online features: the random IDs and the sign-in token that Unity's software keeps, so that the game can sign back in to the same anonymous account

Deleting the app deletes all of this. Your phone's own backups (for example, iCloud Backup) may contain a copy, and those backups are under your control.

If you delete the app before using DELETE MY ONLINE DATA, the key to your anonymous account is lost with it. The game then can't delete your online data for you any more. In that case, contact me (see section 9).

## 3. Online co-op

To play with a friend, the game signs in to Unity Gaming Services anonymously. Unity creates a random player ID; no name, email address, phone number or Apple ID is used.

The host's phone creates a private two-player game and gets a short join code. The code is also shown as a QR code, which holds a `hivestorm://join/…` link. Anyone who has the code can join until the game starts, so only share it with the person you want to play with. Hivestorm doesn't use your camera; you scan the QR code with the iPhone's Camera app.

While you play, game data (such as ship positions and button presses) travels between the two phones through Unity's Relay servers. The servers pass it on in real time and don't store it. The session itself (the two player IDs and the join code) only exists while you play. Your nickname isn't sent to the other player.

## 4. Online high scores (opt-in)

This only happens if you choose a nickname and tap **SAVE & GO ONLINE**. Unity then stores:

- your anonymous player ID
- your nickname: 3–12 letters and digits. The game suggests a made-up name such as NEONFALCON42. Please don't use your real name.
- for each high-score list, your best score, the stage it reached, and when it was posted

There are four lists: solo and co-op, each with a "this month" and an "all time" version. **Anyone who opens the high scores in Hivestorm can see the nicknames, scores and stages on them.**

To keep the lists fair and clean, a small program on Unity's servers (Unity Cloud Code) checks every score and nickname. It refuses scores that are impossible for the stage reached, and names that contain offensive words. When a score is refused, a short technical log entry is kept for 7 days. It contains the game mode, the score, the stage and the player ID.

If you're offline when a game ends, your best unposted score is kept on your phone. It is posted the next time the game goes online.

## 5. Unity Gaming Services and your IP address

The online features run on Unity Gaming Services, from Unity Technologies. Unity processes this data on my behalf as a data processor, under Unity's data processing agreement. The game uses these services: Authentication (anonymous sign-in), Player Names (your nickname), Leaderboards, Cloud Code, and Multiplayer Services with Relay (co-op).

Like any server on the internet, Unity's servers see your device's IP address when the game connects. Unity may use it to work out an approximate location, such as your country or region. For co-op, the game also measures how quickly it can reach Unity's server regions, so it can use the nearest one. Unity lists this as "coarse location" in its privacy disclosures, so it also appears on the game's App Store privacy label. Hivestorm itself never asks for your location and has no access to Location Services. I don't receive or store IP addresses.

Unity's privacy disclosures also say that its Leaderboards service uses the anonymous player ID for analytics, such as statistics about how the high-score lists are used. It isn't used for advertising or for tracking you across other apps. Because Unity declares it, "analytics" also appears next to the player ID on the game's App Store privacy label.

All connections to Unity's services are encrypted, including the co-op game data. Unity is based in the United States and may process data outside the EU/EEA. Unity's data processing terms protect these transfers with the safeguards the GDPR requires, such as the EU Standard Contractual Clauses.

Unity's own privacy policy: <https://unity.com/legal/privacy-policy>

## 6. What Hivestorm doesn't do

- No ads, no advertising identifier (IDFA), and no tracking across other companies' apps or websites
- No analytics, crash reporting or performance reporting added by the game. Unity Analytics, Cloud Diagnostics and similar services are switched off. (For the analytics Unity's Leaderboards service declares, see section 5.)
- No access to your camera, microphone, photos, contacts or location
- No email or password accounts, no social logins
- No in-app purchases
- No selling or sharing of your data

## 7. Why the data is used (legal basis)

- **Co-op and online high scores:** to provide features that you choose to use (GDPR Art. 6(1)(b)). Both are optional, and the game can be played fully offline.
- **Checking scores and nicknames, and the short logs:** my legitimate interest in fair high scores without abuse (GDPR Art. 6(1)(f)).
- **Data on your phone:** stored only because the game needs it to work.

## 8. How long data is kept

| Data | Kept until |
|---|---|
| Anonymous player ID and nickname | you delete them in the game, you ask me to delete them, or the game's online services are shut down |
| "This month" scores | the list resets on the 1st of the next month (UTC). Old months are not archived. |
| "All time" scores | you delete them in the game or ask me to |
| Co-op session (player IDs, join code) | the game ends |
| Log entries for refused scores | 7 days |
| Data on your phone | you delete the app |

## 9. Your rights, and how to delete your data

Under the GDPR you have the right to access, correct and delete your data, to restrict or object to its use, and to receive a copy of it.

- **Delete everything:** go to **HIGH SCORES → CHANGE → DELETE MY ONLINE DATA**, and tap it twice to confirm. This removes your scores from all lists, then deletes your anonymous account and nickname. It also works if you've only played co-op. (It isn't available while a co-op game is running.)
- **Change your nickname:** on the same screen.
- **Anything else, or if you can no longer reach your data in the game** (for example after deleting the app): email me. I don't know who you are, so I can only find your entries if you tell me your nickname and roughly which scores you posted, and when. I may ask for these details to make sure the entries are yours (GDPR Art. 11).
- **Complaints:** you can complain to the Norwegian Data Protection Authority, Datatilsynet (<https://www.datatilsynet.no>), or to the data protection authority where you live.

## 10. Apple, the App Store and TestFlight

Apple runs the App Store and TestFlight under its own privacy policy, as an independent controller.

If you allow it in your iPhone settings ("Share with App Developers"), Apple shares crash reports and usage statistics with me, in a form that doesn't identify you.

If you test a beta through TestFlight, Apple shares with me the information listed in the TestFlight app. This can include the email address you were invited with, install and session counts, crash reports, and any feedback and screenshots you send. I use it only to fix and improve the game. You can stop testing at any time, or ask me to remove you as a tester.

## 11. Children

Hivestorm's online features aren't aimed at children under 13. They collect nothing that identifies a person in real life, the game suggests made-up nicknames, and offensive names are refused. If you're a parent and think your child entered personal information, for example a real name as a nickname, use DELETE MY ONLINE DATA or contact me, and I'll delete it.

## 12. Changes

If the game starts handling data differently, I'll update this page and the date at the top.

## 13. Contact

Stian Andre Olsen, **st-aolse@online.no**
