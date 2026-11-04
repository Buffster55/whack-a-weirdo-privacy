# Whack-a-Weirdo — Privacy Policy

**Last updated:** November 4, 2026
**Developer and data controller:** Robert Vandal, sole proprietor operating as BuffstersQuest, Québec, Canada
**Privacy contact:** buffstersquest-support.skating711@passfwd.com

## About Whack-a-Weirdo

Whack-a-Weirdo is a single-player Meta Quest game playable in virtual reality (VR) and mixed reality (MR), designed for seated play and intended for players age 10 and older. The app is self-certified with Meta as Mixed Ages. It supports offline play and local scores. The game uses an independent Meta age-category service. WORLDWIDE leaderboards remain disabled: current gameplay and scores operate locally, without online leaderboard submissions.

## Information the game handles

- **Local gameplay data:** The game saves local player slots and optional nicknames, completed scores and best results with their VR/MR mode, difficulty and completion time, and settings such as character audio and comfort preferences on the headset. Local save backups may also be retained. The game also writes local functional diagnostic information, such as menu/input counters, current menu state, mode changes and error information. Private testing can additionally produce timing and performance records.
- **Meta account context and User ID (USER_ID):** Whack-a-Weirdo initializes Meta Platform services and checks entitlement using Meta's authenticated current-user and application context. Meta processes this context to handle entitlement and age-category requests. The age service does not separately retrieve or persist the numeric Meta User ID, account name or user profile, and does not link Meta identifiers to local scores.
- **User Age Group (USER_AGE):** The game independently requests and validates the current user's broad age category from Meta's Get Age Category API to support its Mixed Ages requirements. It does not request an exact age or birthdate. The returned category is held only in session memory and cleared when the service processes suspension, session termination or normal shutdown. Unavailable, unknown or unsuccessful results do not block local gameplay. All permitted categories receive the same offline gameplay; WORLDWIDE leaderboards remain disabled.
- **User Profile (USER_PROFILE):** Build 10619 does not use the profile-retrieval or online-leaderboard paths to obtain profile names, usernames or profile pictures during ordinary gameplay.
- **WORLDWIDE leaderboards:** WORLDWIDE is disabled. The current game does not request online leaderboard rankings or submit scores to leaderboards. Local player nicknames are not uploaded to leaderboards, and profile photos are not used. Any future activation of online features will require a separate review and an updated policy describing the processing that will actually occur.
- **Headset and MR information:** Meta Quest processes headset/controller tracking necessary for gameplay and passthrough imagery for MR. Whack-a-Weirdo does not intentionally record, retain, or transmit passthrough camera images, room video, or microphone recordings to the developer.
- **Platform diagnostics (Build 10619):** The submitted game records initialization, entitlement and age-validation outcomes with engine timestamps. The age service retains up to 48 timing records in session memory. Its own diagnostic messages exclude returned age categories, account identifiers, tokens and raw API responses. Captured local logs and troubleshooting copies may remain until removed under the retention practices below. Meta SDK and operating-system logs are separate.
- **Support and privacy requests:** If you email the developer, your address and the information you voluntarily provide are used to reply and handle your request. Support correspondence is handled by Robert Vandal through Proton Mail; please do not send passwords, account secrets, dates of birth, or other sensitive credentials.

## Why information is used

Local information is used to run the game, keep settings and personal bests, and display local results. Meta initialization and entitlement results establish the platform session and entitlement status before the age request. The age-category request supports Meta's Mixed Ages requirements. The current game provides the same local gameplay and score features regardless of the returned category; it does not use age results to enable WORLDWIDE or other social features. Diagnostic outcomes are used to verify and troubleshoot the service. The game does not use third-party advertising or behavioral profiling.

## Children and age-appropriate controls

The app is intended for mixed ages, including players ages 10–12 and 13+, where permitted by Meta's regional rules, and is not intended for children younger than 10. Child, teen and adult players receive the current local gameplay experience. An unknown category, an unavailable service or an unsuccessful age response does not prevent local gameplay. Failures in this service's initialization or entitlement checks also do not block local gameplay. Meta's own account, device and app-access rules remain separate. WORLDWIDE remains disabled for every age category.

## Sharing and service providers

Meta provides the Quest platform and the Platform services used for initialization, entitlement and age-category requests. These are communications with Meta even though online leaderboards are disabled. Meta processes the platform requests and associated account context under its own terms and privacy practices; see the [Meta Platforms Technologies Privacy Policy](https://www.meta.com/legal/privacy-policy/). The game's session-only handling of the returned age category does not determine Meta's retention of its own platform records.

The current game has no independent online player-account or leaderboard backend operated by BuffstersQuest. It has no advertising or third-party analytics integration that sends player data to those providers. Support emails are handled through Proton Mail, which processes messages and related email metadata under its own privacy practices.

## Storage and retention

Local game records, save backups and local diagnostic files can remain in the app's storage until removed. Quest app-data management or uninstalling the game can remove local app data, subject to any Meta device backup/restore features. The current game does not send local gameplay records to a separate BuffstersQuest server.

The age service keeps the returned age category only in the current session's memory. It clears that value when the relevant service session ends or is suspended, including when the app processes focus loss or pause, and during normal shutdown. A new session does not inherit the previous session's category. The game creates no persistent age-category cache or separate age-category database. Clearing the game's session value does not delete records held independently by Meta.

Robert normally archives support correspondence in Proton Mail. Archived messages are retained information, not deleted information, and remain subject to valid deletion requests. Support correspondence is retained only as long as reasonably necessary for support and legitimate recordkeeping obligations. Troubleshooting copies are kept only while needed, with unnecessary copies removed afterward. These records are separate from the game's session memory: clearing the session age value does not delete copied diagnostics or support correspondence. Deletion handling includes applicable messages, attachments and other copies under BuffstersQuest's control, including applicable service-provider copies. Provider-managed backups may remain temporarily under the provider's retention arrangements; immediate erasure of those backups is not promised. Removing an active copy does not by itself prove removal from repository history or independently held third-party records.

## Your choices and deletion requests

You can enjoy local gameplay without online leaderboards. Unavailable or failed age-service responses do not prevent local gameplay. You can remove local game information through Quest app-data management or uninstalling the app; this may erase saved scores and preferences. To ask what information the developer holds about you, request correction or deletion, or raise a privacy concern, email **buffstersquest-support.skating711@passfwd.com** with the subject **“Whack-a-Weirdo privacy request”**. Describe the relevant records or correspondence without sending a password, access token or unnecessary account information. Robert handles valid deletion requests without undue delay, including applicable copies controlled by service providers, subject to legitimate legal retention obligations. Where information must be retained, retention is limited to what is necessary for the obligation. The response explains the verified scope of removal, any applicable retention exception or provider limitation, and any outstanding follow-up. A minimal record of the request and its handling may be kept for necessary accountability, without unnecessarily retaining the information requested for deletion. Submitting a request does not itself erase the records. The developer does not have remote access through the game to delete your headset saves. Records independently held by Meta are governed by Meta's own privacy practices and account controls; contacting BuffstersQuest does not itself delete Meta's records.

## Security and updates

The age service uses Meta's platform interfaces for initialization, entitlement and age-category requests and does not ask you to enter Meta login credentials. Its own diagnostic messages contain outcome labels and timestamps, not the returned age value or account identifiers. This statement is limited to that diagnostic feature, not all SDK or operating-system logs. You can report a suspected security vulnerability to **buffstersquest-support.skating711@passfwd.com** with the subject **“Whack-a-Weirdo security report”**; do not include passwords or access tokens. This policy describes the current functionality. Changes to features or data practices should be reflected in the published policy.

## Contact

**Robert Vandal — sole proprietor operating as BuffstersQuest**  
Québec, Canada  
**buffstersquest-support.skating711@passfwd.com**

_Whack-a-Weirdo · BuffstersQuest · Québec, Canada_
