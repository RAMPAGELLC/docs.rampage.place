# Sentinel Terms of Service (ToS) and Privacy Policy

Effective Date: October 13, 2024

## 1. Introduction

You must be 13 years of age or older to use this application. Sentinel is a Discord-to-Roblox moderation tool designed for banning users across global or specific Roblox experiences. This service is operated by Sentinel Moderation Group (SMG), owned by Metatable Games, a subsidiary of RAMPAGE Interactive. By using Sentinel, you agree to these Terms of Service and the Privacy Policy outlined below.

## 2. Usage of Sentinel

Sentinel is designed for moderation purposes, allowing server administrators to issue bans or revoke bans for users across Roblox experiences. By using the bot, you agree to adhere to the following guidelines:

* **Whitelist Key Requirement**: Usage of Sentinel requires a whitelist key, which can be purchased at [sentinel.metatable.dev/key](https://sentinel.metatable.dev/key). If a key expires or is suspended at the discretion of Sentinel Admins, specific Open Cloud API (OCAPI) endpoints such as `/ban-async`, `/unban-async`, and `/bans` will be automatically disabled. However, the endpoints `/is-banned`, `/pending-unbans`, and `/pending-bans` will remain functional. Certain bot commands within Sentinel will also disable themselves until a new valid key is set via `/setkey`. Sentinel Admins reserve the right to disable keys at any time for reasons such as API abuse or other policy violations.
* **Ban Limits**: Each workspace has a hard limit of 500 bans (including expired bans, as they are retained for history purposes). Communities wishing to exceed this limit must obtain authorization from Sentinel Admins.
* **Ban History Retention**: Ban histories that are marked as inactive or appealed will be automatically deleted within 6 months.
* **Permanent Data Deletion**: Communities, regardless of the whitelist key's status, will always have access to the Sentinel bot command `/uninstall`, which will permanently delete all data associated with the guild, including bans, linked experiences, and other relevant information.
* **Appropriate Use**: You agree not to misuse Sentinel for malicious purposes, such as infringing upon the rights of other users.
* **Compliance with Roblox and Discord Policies**: You are required to follow both Roblox’s and Discord’s Terms of Service and Community Guidelines when using Sentinel.
* **Data Integrity**: All data managed by Sentinel is related to moderation actions (such as bans) and is handled with respect to privacy as described below.

## 3. Data Collection and Usage

Sentinel collects and stores the following non-sensitive data:

* **Discord User IDs**: Collected when a moderation action is performed (e.g., issuing or revoking a ban).
* **Roblox User IDs**: Collected to associate moderation actions with Roblox users in the context of banning.

Data is only stored and used for the purpose of enabling moderation actions within Roblox experiences, specifically when:

* A ban or unban action occurs.
* A workspace is created in the Sentinel system.

## **3.1 Data Storage**

Data is stored in a secure database, managed by SMG, and includes:

* **GUIDs**: Globally unique identifiers for each ban and workspace.
* **Workspace Associations**: Identifying which workspace (Roblox experience) a ban relates to.
* **Ban Status**: Whether the ban is active and if it applies globally across all experiences or just one specific experience.

## **3.2 Data Access**

Only authorized engineers working under Metatable Games can access this database.

## **3.3 Data Retention**

We retain the collected data for as long as necessary to provide our services and fulfill moderation actions. Users may request the removal of data where applicable.

Due to bans not being tied to any Personal-Identifiable Information (PII), we will not accept requests to "Forget" your ban. Bans can only be deleted by Authorized Workspace Administrators and the Workspace Owner.

## 5. Liability

SMG is not liable for any damages or losses resulting from misuse of the Sentinel system. By using Sentinel, users agree that the system is used at their own risk and in accordance with Roblox and Discord policies.

## 6. Changes to the Terms and Privacy Policy

We reserve the right to modify these Terms of Service and the Privacy Policy at any time. Users will be notified of any changes through a global announcement via the Sentinel Bot.

## 7. Contact

For any questions regarding these Terms or the Privacy Policy, or to request data access or deletion, you can contact SMG at support@rampagestudios.org.

