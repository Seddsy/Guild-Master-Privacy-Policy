# Guild Master Privacy Policy

**Last updated:** 6 November 2026  
**Application:** Guild Master 1.1.4

Guild Master helps Root communities organize guilds, a starting five and a separate Coach, team preparation and Renown. This policy explains the information used by those features and optional Master Series connections. It supplements Root's privacy information and any separate notices from your community.

## 1. Operator and responsibilities

**Developer and operator:** Michal "Seddsy" Myška  
**Privacy contact:** [seddsylive@gmail.com](mailto:seddsylive@gmail.com)  
**Suggested email subject:** Guild Master privacy

Guild Master is independently developed. For personal information in App Data, Root's [Developer Terms and Data Processing Addendum](https://www.rootapp.com/developer-terms-of-service) designate **Root Communications, Inc. as controller** and the app operator as its processor. We handle that information to provide the app under Root's instructions. Root explains its own processing in its [Privacy Policy](https://www.rootapp.com/privacy-policy).

Server owners configure community catalogs, eligible voice channels and Renown rules. Guild leaders manage membership and team assignments; leaders and Coaches contribute preparation records. They remain responsible for their own community activities, downloaded copies and information collected outside the app. Direct correspondence with the operator is described in Section 9.

This notice does not request blanket consent. Installing or opening the app, joining a guild or remaining in a voice room does not itself establish a legal basis for every use or disclosure. The responsible controller must establish the appropriate basis and obtain separate consent where required.

## 2. Information and sources

Information comes from Root, member actions, guild leaders, Coaches, the Server owner and explicitly connected applications. A person can appear in records supplied by somebody else without personally opening Guild Master.

- **Identity and access:** Root community and user IDs, current display names or nicknames, community ownership, membership checks and available community join-time information. These checks associate records with members and prevent old guild access from returning after a community departure and rejoin.
- **Guild organization:** guild IDs, names, tags, mottos, introductions, recruitment expectations, sought game roles, applications and their status, invitations and their sender, recipient, status and expiry, membership and leadership history, assigned ranks, selected game roles, the main lineup and Coach assignment.
- **Community settings:** rank and game-role catalogs, default rank, selection limits, Coach title, guild capacity, voice-channel IDs and names, exclusions, reward values, eligibility conditions, weekly reset timezone and published policy versions, authors and timestamps.
- **Shared preparation:** availability windows, dates and timezones, training titles and details, Yes/No/Maybe responses, goals and progress, practice plans, links to training, shared reviews and their authors and timestamps. Free-text fields can contain information entered by a member or staff member.
- **Private coaching feedback:** author and recipient IDs, guild reference, feedback text, creation details and access-revocation metadata. Section 4 explains its narrower visibility.
- **Voice participation:** presence in owner-selected voice rooms, person/user IDs and relevant self-deafened or administrator-deafened status. Eligible records include channel and guild references, membership references, verified time intervals, applicable policy and resulting contribution records. Room queries can initially return all person occupants; the collector filters out people who do not belong to a guild before saving Guild voice intervals.
- **Verified events:** connected source and installation identifiers, occurrence and event references, title, event type, occurrence/completion time, verification information, revisions or cancellation, and the verified participant-ID set. An accepted occurrence can contain up to 200 verified participants in total, **including people who do not belong to a guild or earn Renown**. The app retains the source fact and historical membership associations to calculate and correct contributions.
- **Guild Wars:** nomination, lobby, game and result IDs; both guilds; historical five-player rosters; the separate Coach reference in nominations; match times, outcomes, treatment such as played/forfeit/excluded, revisions, acknowledgement and rating records. Game Master supplies the verified roster and result data through the configured connection.
- **Operational records:** member-associated actions and timestamps, storage revisions, membership history, reward sources, duplicate-prevention identifiers, delivery receipts, installation and session metadata, saved connection requests and server-side authentication credentials. Credentials are excluded from ordinary member views and readable exports.
- **Direct support:** your email address, message and any information you choose to send to the contact above. The app does not obtain your email address or password from Root for these features.

Voice processing observes room presence and status, **not conversation audio, speech content or speaking activity**. Guild Master does not record voice or video. When collection is configured and the native service is running, eligible room presence can count even if a member has not opened the app. Self-muting is not a promise that presence will stop counting; ask the Server owner which rooms and exclusions apply.

Enter only information needed for guild work. Do not put passwords, access tokens or unnecessary sensitive information in profiles, plans, reviews or feedback. Guild chat is not enabled in this version; private feedback is a coaching record rather than a general messaging service.

## 3. Purposes and calculations

The app uses information to verify access, maintain guild membership and recruitment, organize the main team and Coach, share preparation, deliver private feedback to its entitled readers, calculate Renown and standings, apply published limits, reconcile corrections, prevent duplicate effects, recover permitted shared records and provide support.

Renown calculations use confirmed Guild War results and opponent strength, plus eligible voice and event contributions under the Server owner's published policy. Activity contributions have separate conditions and caps and do not increase the opponent-strength calculation. These automated calculations affect community guild standings. Guild leaders make membership and lineup decisions.

For a recorded mistake, ask the relevant guild leader or Server owner to review the guild record. Game results need correction in Game Master; event participation needs review by the responsible Event Master organizer. A source correction and a personal-data erasure request are different processes.

We do not sell or rent app records, use them for advertising or send them to an AI service for analysis or training. The app does not build an outside profile combining a member's activity across unrelated communities.

## 4. Who can see information

- **Community members** can see guild directory summaries, leaders, starting lineups and Coaches and their visible game-role selections, member counts, Renown standings and community-visible competition results, including historical player rosters. These views are inside the relevant Root community, not an app-created public internet directory.
- **Current members of a guild** can see its full roster and the shared preparation available to that guild, including colleagues' availability and training responses. Members control their own availability and responses.
- **Guild leaders** manage their guild's membership, applications, invitations, rank assignments, lineup and Coach. Assigned Coaches can manage preparation; a descriptive rank called Coach or Leader does not itself grant these rights.
- **Server owners** manage community catalogs, Renown policy, connection administration and authorized community operations. They can inspect community Renown records and export full organizational rosters and ranks. Ownership alone does not give access to another guild's private feedback or all its preparation.
- **Private feedback** is readable only by the recipient and a still-authorized author while both remain in the same guild. The author must currently have leader or Coach preparation rights. Loss of that role removes author access while it is absent. A guild/community departure permanently revokes the original feedback record; rejoining does not reactivate it. The recipient cannot delete the author's feedback through the current feedback tool.
- **Voice and event detail** is scoped separately: detailed voice progress is available to the affected member, own-guild ledger entries can identify contributors, and the Server owner can inspect the community ledger. Displayed event contribution entries use event references, titles and counts; they do not expose the complete source attendee array to ordinary members.

Root and infrastructure providers process information needed to run their services. Authorized operator access may be necessary for support, maintenance, security or a privacy request. Private feedback is stored in the app's private server state and internal recovery checkpoint; it is not end-to-end encrypted content that only its readers could ever decrypt.

People can retain information they have already read or downloaded. Later access revocation cannot recall their copies.

## 5. Storage, providers and connections

### Root hosting

Production state is stored in Root's private, installation-scoped app datastore. The app retains its primary state, a previous internal recovery checkpoint and separate connection state. Root provides the platform identity, hosting, transport and infrastructure backups. Local developer previews use fictional data and are separate from production installations.

### Master Series Relay

Optional connections are configured by the **current Server owner** for compatible installations in the same Root community. The operated Relay endpoint is [game-master-relay.onrender.com](https://game-master-relay.onrender.com), hosted on **Render**. Its processing includes community and installation identifiers and names, setup/invitation and authentication metadata, persistent workspace/session state, queued messages and delivery receipts. See [Render's privacy information](https://render.com/privacy).

Guild Master sends five-player nomination information, guild and match references and the separate Coach reference to Game Master, and receives nomination acknowledgements and verified results/corrections. Compatible Event Master connections send the verified event information and participant sets described in Section 2. Event contributions require a Relay deployment supporting the Guild event route; app installation alone does not establish it.

The Guild connection does **not** transmit private coaching text, availability, training plans, shared review text, chat or audio. Quarter Master's economy and rewards are separate; Guild Renown does not automatically create Quarter Master payouts. The adapters do not support cross-community Guild competition.

Pairing does not by itself provide a legal basis for disclosure. Connected processing must remain within Root's permitted instructions and applicable law. Relay requests originate from app servers rather than a separate tracking connection from each member's browser. A receiving app can retain already received records under its own policy after a connection stops.

### Devices, tutorials and external pages

The app can store a light/dark theme preference in device local storage. The app code has no advertising cookies, third-party analytics SDK or tracking beacon. Root's client and hosting have their own storage and telemetry practices.

Help videos are stored with the app on Root and delivered through Root when you select **Load video**. Small poster images remain part of the interface. Tutorials use fictional example data and do not require an external video account. Loading a video requires an active Root connection. Closing Help or hiding the app stops requesting further video data and releases the player; a request already sent may still finish. The player does not record the viewer or upload a viewing history to a separate tutorial service.

Opening an external link, including this policy on GitHub, involves that destination's ordinary browser/network processing. GitHub's handling of visits to its pages is described in its [Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). We do not publish guild member records in the policy repository. Direct email handling is described below.

**International processing:** Root's [Privacy Policy](https://www.rootapp.com/privacy-policy) describes storage in the United States. Relay and other service-provider processing may also occur outside your country. This notice does not promise EEA-only hosting. Applicable transfer safeguards and information about a particular transfer depend on the responsible controller and service arrangements.

## 6. Retention, deletion and recovery

Guild, profile, preparation, Renown and historical competition records have **no universal automatic age-based deletion schedule** in this version. They remain to support membership, history, correction and replay until removed through an authorized operation or the privacy-request process. Capacity limits and the shorter history shown on screen are not automatic deletion schedules.

- Leaving a guild or community removes current membership and assignments and revokes affected availability/feedback access. It does not automatically erase profiles, historical rosters, results, audit IDs, recorded voice/event facts or revoked feedback text.
- An invitation's expiry prevents acceptance; expiry alone does not erase its record. Disconnecting a companion app does not erase source facts or rewards already recorded in Guild Master.
- Members can remove their own availability. Authorized staff can remove supported shared preparation records, and a still-authorized feedback author can remove their own feedback. These controls remove the selected current-state record; related audit information or a prior private checkpoint can remain.
- The previous full private checkpoint may contain a record deleted from current state until that checkpoint is replaced. The owner-facing **Restore shared preparation** operation can restore earlier training, goals, plans and reviews. It does not restore old membership grants, private feedback, availability or individual training responses.
- Current persistent Relay routes remain until disconnected, revoked or otherwise closed, rather than having a guaranteed short expiry. Acknowledgement clears a queued transport payload for its recipient. Disconnecting an ecosystem route suspends exchange but can preserve unacknowledged payloads, saved requests, state and receipts for recovery; it is not a transport-data erasure action. Installation and ecosystem metadata, companion histories and provider logs have separate lifetimes.
- Downloaded exports, copied text and platform/provider backups are separate copies. App changes cannot remotely delete files held by recipients, and no instant erasure of every backup copy is promised.

These implementation details do not override applicable deletion duties. Data in the operator's control must be removed when required by Root's instructions or law, including at the end of processing, except to the extent applicable law requires retention. Root controls decommissioning of its hosted instances and platform backups. Section 8 explains how to request correction or deletion.

## 7. Member choices and exports

Members can update their permitted profile and game-role choices, manage their own availability and training responses and leave a guild subject to leadership-transfer rules. Ask the Server owner about allowed voice channels, eligibility and policy settings. Leaving a configured voice room stops new presence there from qualifying; it does not erase previous observations. There is no member-level voice-tracking opt-out switch in this version.

**Download my data** provides a readable export of supported, authorized personal records, such as the profile, membership, own pending applications, visible own availability and entitled private feedback. It is not a complete copy of every invitation, training response, voice observation, event fact or historical competition record concerning you.

The **Server owner's community export** contains organizational rosters and ranks, settings and authorized operational/competition information. Shared preparation in it is limited to the owner's own guild; it excludes other people's private feedback and connection credentials. An export is not a complete database backup, a deletion action or an import file.

The app has no one-click tool to erase all information about a person. The export and record-editing tools do not replace the privacy-request process.

## 8. Privacy requests and rights

For Root-controlled application data, contact **[Root Support](https://www.rootapp.com/support)**. You may also email **[seddsylive@gmail.com](mailto:seddsylive@gmail.com)** with the subject **Guild Master privacy**. App Data requests received by the operator will be promptly referred and forwarded to Root; we assist under its instructions.

Identify the relevant Root community and your user ID if available, and describe the records or request. Send only what is reasonably needed for verification. Do not send passwords or authentication tokens or publish personal records in a public GitHub issue.

Depending on applicable law and the circumstances, rights can include access, correction, erasure, restriction, portability and objection, and withdrawal of consent where processing relies on consent. Where GDPR applies, the responsible controller normally has one month to respond and must explain a permitted extension. The [EDPB's guide to individual rights](https://www.edpb.europa.eu/sme/be-compliant/respect-individuals-rights_en) describes the conditions and exceptions.

You may complain to the competent supervisory authority. In the Czech Republic, this is the [Office for Personal Data Protection](https://uoou.gov.cz/).

## 9. Direct correspondence

For email sent directly to the operator outside Root-controlled App Data, **Michal "Seddsy" Myška** is the controller. We use your email address and message to answer, troubleshoot or route the request and retain it as needed to resolve the matter and meet applicable obligations. Where GDPR applies, the basis is our legitimate interest in responding to inquiries, or an applicable legal obligation.

The mailbox uses Gmail, subject to [Google's Privacy Policy](https://policies.google.com/privacy). App Data requests are forwarded to Root as described above.

## 10. Security

The app uses verified Root identity, server-side access checks, community-scoped storage, filtered views, separate connection credentials, revision checks and delivery receipts. Connection secrets are kept server-side and excluded from ordinary client responses and readable exports. Private app storage is an access boundary; this policy does not assert independently verified platform encryption at rest or absolute security.

Keep setup codes and downloaded exports private. Report suspected exposure to the operator and Root Support so the incident can be investigated under the applicable process.

## 11. Age requirements and changes

Use of Guild Master is subject to Root's age requirements and community rules. Root currently states that its service is not intended for children under 16. Guild Master does not independently collect or verify birth dates. Contact Root Support or the operator if you believe an ineligible child appears in app records.

We will update this notice when app practices, features or providers change and revise the date above. Material changes will be communicated through the app listing or another appropriate channel where required.

For Guild Master privacy questions, contact **Michal "Seddsy" Myška** at **[seddsylive@gmail.com](mailto:seddsylive@gmail.com)**.
