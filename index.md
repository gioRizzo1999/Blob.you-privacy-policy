# Privacy Policy for Blob.you

**Policy version:** 6.0 (ad-enabled release)

**Effective date:** September 12, 2026

**Last updated:** September 12, 2026

Giovanni Rizzo, operating as FirstBitStudio ("FirstBitStudio," "we," "us," or "our"), provides the mobile game **Blob.you** (the "Game"). This Privacy Policy explains the information processed by the Game and the choices available to players.

This policy applies to the Android and iOS versions of the Game, including Android APKs distributed directly or through itch.io. Advertising processing described here applies only to ad-enabled builds when the player allows ads; it does not mean that older ad-free builds have started collecting advertising data. Stores, download platforms, and third-party websites opened outside the Game have their own privacy policies.

## 1. Current Version at a Glance

- The Game does not require or provide player accounts.
- Ad-enabled mobile builds offer optional rewarded revives and occasional ads between runs using Unity LevelPlay and Unity Ads, after the player allows ads.
- The Game does not contain in-app purchases, social features, Unity Analytics, or another gameplay-analytics service. Ads are configured to be non-personalized. The Game sends advertising-ID opt-out settings and does not request iOS tracking permission; other technical identifiers may still be processed as described in Section 3.
- Unity Engine Diagnostics and Unity cloud crash reporting are disabled in the current version. This does not disable the advertising SDKs' own diagnostics when ads are enabled.
- The Game does not send the player's mass, score, captures, survival time, or run-start/run-end events to a gameplay-analytics service. The advertising services process information as described below when ads are enabled.
- Basic progress and settings are stored locally on the player's device.
- Selecting Not Now leaves advertising uninitialized on first launch. Ad Privacy in the menu and replay screen lets the player change this choice. Turning ads off stops new ad loads and displays from the Game and discards loaded ads; it does not unload an already initialized SDK or delete information already received by the advertising services. See Sections 3 and 9.
- We receive contact information only when someone voluntarily contacts us outside the Game, for example by email.
- Earlier Google Play testing builds had different Unity Analytics and Diagnostics behavior. Section 4 explains that historical processing.

## 2. Information Stored Locally on the Device

The Game uses Unity's local `PlayerPrefs` storage for:

- the player's best mass and total-absorbed record;
- completed onboarding steps;
- whether one-time tutorial or gameplay messages have already been shown; and
- the player's ad privacy choice.

This information is used to preserve progress, avoid repeating completed instructions, and remember the player's advertising choice. The current Game does not send progress or onboarding records to FirstBitStudio, Unity Analytics, or another analytics provider. Advertising privacy signals are sent to the ad services when initialized. The advertising SDKs may also use local storage for their settings, identifiers, and cached advertising content after ads are enabled.

Local information remains on the device until it is overwritten, the Game's local storage is cleared, or the Game is uninstalled, subject to device-level backup or restoration features controlled by the operating system or player.

## 3. Information Processed Off the Device

### Advertising in Ad-Enabled Builds

After the player selects **Allow Ads**, Unity LevelPlay manages requests and Unity Ads supplies ads. These services may process IP address and approximate location derived from it, device or app-installation identifiers and SDK-generated user identifiers, device model and operating system, language, network information, SDK/app versions, privacy signals, SDK session information, ad impressions, video completions, clicks, and SDK diagnostics. Processing supports ad delivery, measurement, service improvement, reliability, and fraud prevention. This data goes to Unity and the parties described in its advertising privacy policy, even though FirstBitStudio does not operate its own advertising server. We can view advertising performance and revenue reports through the providers' dashboards.

The Game sends settings that decline personalized advertising and opt out of sale/sharing, together with LevelPlay's advertising-ID opt-out setting. The Android build configuration removes the advertising-ID permission, and the Game does not request App Tracking Transparency permission on iOS. These settings do not mean that all identifiers or network data are absent: non-personalized ads still involve technical data processing. We do not supply names, email addresses, precise location, or game scores to the advertising SDK.

Rewarded ads require a separate, voluntary selection of **Revive**. Once ads are allowed, interstitial ads may also appear between runs without a separate choice for each ad. Ordinary replay remains available without selecting a rewarded ad. Declining advertising does not prevent ordinary gameplay, but ad-supported revives are unavailable while ads are off. Withdrawing the ad choice stops new ad requests from the Game. It does not unload an already initialized SDK: outstanding requests and SDK operational processing may continue during the current app session. On later launches with ads off, the Game does not initialize the advertising SDKs.

Unity may act as an independent data controller for its advertising-related processing, rather than solely processing information on our behalf. Its processing and rights options are described in its [Game Player and App User Privacy Policy](https://unity.com/legal/game-player-and-app-user-privacy-policy). The game is configured for Unity Ads as its only ad network; adding networks requires an updated notice.

Selecting an advertisement may open an advertiser's website or an app-store page. Any information provided there is subject to that destination's privacy policy.

If a player voluntarily submits feedback or reports an advertisement through a provider's reporting tool, the provider may also receive the report contents and related support information under its own privacy policy.

### Contact Correspondence

If a player, parent, or guardian contacts us by email, we receive the sender's email address, display name, message, attachments, and any other information they choose to provide. This information is not collected automatically by the Game.

We use correspondence only to respond to support questions, complaints, and privacy requests; fulfill legal obligations; maintain necessary records; and protect our legal rights. We do not use support or privacy correspondence for marketing. Please do not send information that is not needed for the request.

## 4. Earlier Google Play Testing Builds

Some Google Play testing builds distributed before August 12, 2026 contained **Unity Analytics**. Analytics was optional and started only after the player selected **Allow**, but the choice was not limited to adults. When allowed, Unity Analytics could process:

- IP address and approximate location derived from it;
- a randomly generated installation or analytics identifier;
- device, operating-system, platform, language, app-version, and SDK information;
- session, event, and app-lifecycle information;
- app diagnostics or performance information generated by the Analytics SDK; and
- developer-defined gameplay events, including run start and end, survival time, maximum mass, blobs eaten, escape attempts, successful escapes, ending reason, and whether the player quit while alive.

Those testing builds also enabled **Unity Engine Diagnostics** independently of the Analytics choice. Unity could automatically process crash reports, exception logs, Application Not Responding reports, performance and responsiveness telemetry, device and operating-system information, build information, and an installation or device identifier.

These earlier builds are being replaced or withdrawn. The current project has removed the Unity Analytics package and gameplay-event code, and has disabled Unity Engine Diagnostics and cloud crash reporting. Players with an earlier testing build should update to the newest available version.

Historical Analytics and Diagnostics information was used only to understand gameplay, improve balance, and diagnose technical performance. It was not used for advertising, credit decisions, or cross-app behavioral profiles.

## 5. Legal Bases

Current local game information is processed as necessary to provide requested game functionality. It remains on the player's device and is not received by FirstBitStudio.

We rely on the player's consent to enable advertising SDKs and related optional device access. Unity describes its own legal bases for its processing, including legitimate interests for contextual advertising and service security, and legal obligations, in its privacy policy. Allowing ads in the Game is not consent to personalized advertising: the Game continues to send non-personalized settings. The ad choice may be withdrawn in **Ad Privacy** without preventing ordinary gameplay. Withdrawal does not affect the lawfulness of processing based on consent before withdrawal.

When someone contacts us, we process the correspondence based on our legitimate interest in responding to inquiries and operating support and, where applicable, to comply with legal obligations. Providing contact information is voluntary, but we may be unable to answer or fulfill a request without enough information to understand it.

Earlier optional Unity Analytics information was processed after the player selected **Allow**. Earlier Engine Diagnostics information was processed to identify crashes and technical problems. Players may contact us regarding historical information as described in Section 9.

## 6. Service Providers and Disclosure

The current Game does not send developer-defined gameplay analytics or Unity Engine Diagnostics. Ad-enabled builds send advertising-related information to Unity LevelPlay and Unity Ads after the player's choice, as described in Section 3.

Messages sent to `firstbitstudio.dev@gmail.com` are delivered and stored using **Google's Gmail service** so that we can manage correspondence. Google's privacy policy is available at:

https://policies.google.com/privacy

The public copy of this policy is hosted using **GitHub Pages**. Opening the Privacy Policy link leaves the Game and opens the page in the device's browser. GitHub may process ordinary website-request information under its own privacy statement:

https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

The policy website's current theme also loads a navigation script from **Cloudflare's cdnjs** content-delivery service. This gives Cloudflare ordinary request information, such as the visitor's IP address and browser information, to deliver and secure that resource. This website request is separate from the Game's advertising choice. See [Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/).

For the historical processing described in Section 4, information was provided to **Unity Technologies** and its infrastructure providers to operate Unity Analytics and Engine Diagnostics. Unity's game-player privacy policy is available at:

https://unity.com/legal/game-player-and-app-user-privacy-policy

We may disclose information when reasonably necessary to comply with law, enforce legal rights, protect players or the public, or respond to valid legal process. We do not sell personal information for money. The advertising integration sends a do-not-sell/share signal and does not request personalized or cross-app behavioral advertising.

## 7. Data Retention

Local game information is retained as described in Section 2.

Advertising information is retained under Unity's applicable privacy policy. Retention depends on the service relationship, fraud-prevention needs, legal and accounting obligations, and the establishment or defense of legal claims; there is no single fixed period promised here for all advertising data. Disabling ads does not automatically erase previously transmitted information. Contact us or Unity to request help with access or deletion.

Support and privacy correspondence is retained only for as long as reasonably needed to resolve the inquiry, maintain necessary records, comply with legal obligations, or establish, exercise, or defend legal claims.

Historical Unity Analytics and Diagnostics information is retained according to Unity's applicable settings and terms. Unity states that raw Analytics event data is generally retained for 13 months and then automatically deleted, while some dashboard or player-profile metrics may remain until deletion is requested or initiated. FirstBitStudio does not maintain a separate server-side copy of the Game's raw Unity Analytics events.

## 8. Security

The Game keeps ordinary game progress on the device and does not transmit gameplay analytics or Unity Engine Diagnostics. Advertising introduces the data processing described above. Unity's published SDK disclosures describe encryption in transit for information collected by [LevelPlay](https://docs.unity.com/en-us/grow/levelplay/platform/legal-resources/google-data-safety-questionnaire) and [Unity Ads](https://docs.unity.com/en-us/ads-android/4.20.0/privacy/developer-consent/disclosures/google-data-safety). No storage or transmission system can be guaranteed to be completely secure. We use reasonable measures appropriate to the information we process.

## 9. Player Choices and Privacy Rights

Depending on where a player lives, the player may have rights to request access, correction, deletion, restriction, objection, or portability and to complain to a local data-protection authority.

Because the Game has no player account, there is no Game account to delete. Clearing the Game's storage or uninstalling it removes ordinary local game information, subject to operating-system backups.

To withdraw the ad choice, open **Ad Privacy** on the main menu or replay screen and select **Not Now**. This stops new ad requests from the Game and discards loaded ads, subject to the SDK-session limitation explained in Section 3. Requests concerning advertising information can be directed to us or to Unity at **DPO@unity3d.com**, specifying Blob.you and the relevant service, such as Unity Ads or LevelPlay. Where available, an ad's privacy icon also provides Unity's privacy options. Uninstalling the Game does not itself delete advertising information held by a provider.

For questions or requests concerning contact correspondence or information sent by an earlier testing build, contact us using Section 13. We may need an installation identifier or other limited information, if available, to locate historical Unity data and may need to verify the request where required by law.

Players may also complain to the supervisory authority where they live or work or where an alleged infringement occurred. In Italy, the supervisory authority is the [Garante per la protezione dei dati personali](https://www.garanteprivacy.it/diritti/come%20-agire-per-tutelare-i-tuoi-dati-personali/reclamo).

## 10. International Data Transfers

Google, GitHub, Cloudflare, Unity, and their infrastructure providers may process information outside the player's country when someone contacts us, opens the externally hosted policy, uses enabled advertising, or when historical Unity information is retained or deleted. Unity identifies processing locations including the United States and Israel. For relevant transfers outside the EEA or UK, providers describe safeguards such as adequacy decisions or Standard Contractual Clauses in their linked policies. Players can contact us for help locating applicable safeguards, or contact the relevant provider to request a copy; Unity provides this option through the contact details in its privacy policy.

## 11. Children and Teen Players

The Game's intended audience is age 13 and above; it is not directed at children under 13. Advertising is configured for non-personalized ads with the privacy settings described in Section 3. The same ordinary gameplay is available when advertising is declined. Where local law requires a parent or guardian's authorization for consent, a minor should not enable ads without that authorization.

If a parent or guardian believes that information from a child was processed without the required authorization, including through advertising or an earlier testing build, they may contact us using Section 13. We will take reasonable steps to assist with deletion where required and technically possible.

## 12. Changes to This Policy

We may update this Privacy Policy when the Game, its services, or legal requirements change. The updated policy will show a revised version and date. If a change materially affects previously collected information, we will provide additional notice or request consent where required.

## 13. Support

For help with Blob.you, bug reports, or feedback, contact firstbitstudio.dev@gmail.com. Please include your device model, game version, and a short description of the issue.

## 14. Contact Us

**Developer and data controller:** Giovanni Rizzo, operating as FirstBitStudio  
**Privacy contact email:** firstbitstudio.dev@gmail.com  
**Contact location:** Brescia, Italy
