# Homenari: Chores & Calendar Privacy Policy

Homenari: Chores & Calendar is developed by Optimus.NTL.

## Data we use

Homenari lets two adults organize chores and plans in a private household. We use the following information to run your account and sync your household.

- **Google provider account identifier, email and display name received during sign-in.** Google and Firebase verify your identity. Your Google email is kept out of the household roster.
- **Homenari account ID, authentication credentials and session state.** We use these to restore your session and authorize requests. Homenari receives authentication tokens through Google sign-in and does not ask for your Google password.
- **User-chosen display label.** Your label appears in the household and identifies the person assigned to a shared item.
- **Household ID, user-entered household name, household time zone, creation and update timestamps.** These identify your household and keep shared dates and times consistent.
- **Membership records including account IDs, user-entered display names, roles and join or leave status.** These control access and identify the household owner and member.
- **Invitation identifier, token or code, household and creator IDs, issue and expiry times, and redemption or revocation state.** We use these to issue and validate single-use invitations. The app uses the share option you choose and does not access your contacts.
- **Chore ID, title, optional owner, due date and time, recurrence rule, occurrence IDs and dates, completion or missed status, timestamps and needed actor references.** These records make the shared chore schedule and completion history work.
- **Event ID, title, all-day date or timed start and optional end, creation time zone and update timestamps.** These records make shared plans appear consistently on both devices.
- **Write identifiers, entity revisions, retry outcome and submitted edits.** These let us synchronize changes, recover from interruptions and avoid applying the same change twice.
- **Account deletion request reference, account identifier, verification and completion state.** We use these to verify and process deletion and show its progress to the requester.
- **Firebase Authentication IP addresses, app ID, and SDK and platform user-agent metadata.** Firebase uses this information for service operation and abuse prevention. Signed-in Firestore requests include your Firebase user ID. [Firebase Android data disclosure](https://firebase.google.com/docs/android/play-data-disclosure)
- **Cloudflare request and invocation metadata.** Cloudflare processes connection and request metadata to operate the service, troubleshoot errors and protect it against abuse. [Cloudflare Workers Logs](https://developers.cloudflare.com/workers/observability/logs/workers-logs/)

Homenari stores an offline household copy, edits waiting to sync, and drafts on your phone. A submitted edit is sent when the phone reconnects. Reminder preferences, followed events, local delivery markers, device display preferences and notification permission state are used locally. The app proposes your device's time zone when you create a household, and saves the household time zone you confirm.

## Who can access your data

Google Firebase provides sign-in and cloud data storage. Cloudflare Workers processes household commands and supports Homenari's invitation and account deletion services. The current household member can see your display label and the household's shared data. Invited people receive only the invitation you share with them. We do not sell personal information or use it for advertising.

Data sent by Homenari to its services travels over HTTPS. We limit access to shared records to authorized household members. Account verification is required before an account deletion request is accepted.

## Retention and deletion

While your account is active, we keep the identity and data needed to maintain it. Shared records remain available to an active household until removed or the household closes. Signing out clears the active local household copy and queued changes and cancels reminders. Leaving a household ends your access. Account deletion also removes your Homenari account and associated data.

To request deletion, open **Household settings → Account → Delete account** and confirm with the same Google account. If you cannot access the app, email the privacy contact below for help requesting account deletion. Deletion runs in the background. You can check its status with your private reference, which expires seven days after completion.

If an adult stays in the household, they retain the shared schedule and completion history. We remove account references from the retained history and unassign open chores owned by the deleted account. If you are the last adult, the household and its shared records and invitations are deleted. Titles are supplied by members. Remove personal details you entered into shared titles before leaving if you want them removed from retained records.

Google documents separate retention for security and backup systems. Firebase Authentication retains recorded IP addresses for a few weeks and removes other authentication information from live and backup systems within 180 days of a deletion request from the Firebase customer. [Firebase privacy and security](https://firebase.google.com/support/privacy)

## Privacy contact

For privacy questions, requests about your data or help with account deletion, contact Optimus.NTL at [88luan@gmail.com](mailto:88luan@gmail.com).
