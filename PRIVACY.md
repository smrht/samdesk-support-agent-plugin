# SamDesk Support privacy

The plugin reads inbox names, contact names, selected conversation metadata and public incoming/outgoing message text from organizations explicitly approved through OAuth. SamDesk rechecks membership and inbox rights for every call. It does not return private notes, attachments, channel settings or separate contact email/phone fields. Personal information can still appear inside message text.

The package contains no independent storage or telemetry. SamDesk stores the OAuth connection and approved organization IDs, but does not create an additional conversation copy for this plugin. Retrieved text is sent to your chosen AI host and is subject to that host's privacy settings and retention. Revoking access stops future reads and token refresh; it does not erase prior host chats.

Manage access: https://samdesk.nl/support/plugin/connections/
Full policy: https://samdesk.nl/support/plugin/privacy/
Contact: support@samdesk.nl
