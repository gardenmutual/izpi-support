# IZPI Support and Privacy

Last updated: September 25, 2026

IZPI helps a household make plans, complete chores, practice remembering steps, and celebrate progress. Each household creates its own private space. IZPI does not preload or publish anyone's family roster.

## Support

For general bugs or feature feedback, use [IZPI support issues](https://github.com/gardenmutual/izpi-support/issues). Do not put private family information in a public GitHub issue. For an account or data-privacy request, use the in-app deletion control or contact the developer through the App Store listing.

## Information IZPI handles

- Account email, a password processed by our authentication provider, and account/session identifiers are used to sign you in. IZPI does not receive or store your plaintext password.
- A household creator may enter a household name, member names or nicknames, adult/child profile labels, chores, routines, and progress. Invited members of that household can view its shared board.
- Invite codes are one-use and expire after 24 hours. The server stores a hash of each invite code, not its plaintext value.
- Basic service logs and timestamps may be processed to operate and secure the service.

IZPI uses Supabase to provide account authentication and a database hosted in the United States. Access to household records is restricted by signed-in membership checks enforced in the database. IZPI does not sell personal information, show ads, or use third-party advertising analytics.

This version does not request location permission or provide location sharing. It does not send remote push notifications. Data is transferred over encrypted network connections; a signed-in device may retain an authentication session until sign-out.

## Children and families

Adults should create and manage household membership and supervise children's use. A child's profile can be a nickname. Do not put birth dates, medical details, or precise location into a profile or mission. IZPI is an organizational game, not a medical or emergency service.

## Deletion

In Settings, a signed-in user can choose **Delete my IZPI account**. This permanently removes their sign-in account and household membership. If they own a household, deletion also removes that household and its shared profiles and missions for all members. If they are an invited member, shared household content may remain for other members until the household owner removes it. A user can also sign out without deleting their account.

## Policy changes

We will update this page and the App Store privacy disclosure before releasing a version that changes what data IZPI collects or shares.
