# Mission

Build Billiverse: a Svelte-powered frontend with a Cloudflare Workers HonoJS backend (and a sprinkle of Azure OpenAI magic) to scan, analyze, and manage bills—so users never miss a due date (or lose a bill in a sock drawer) again.

## Steps

### Frontend (Svelte)

Create a clean, friendly UI for uploading bill scans, viewing bill details, and tracking due dates.

Add notifications for upcoming due dates (because nobody likes late fees).

Display extracted bill details: sum, bank account, due date, and other essentials.

### Backend (Cloudflare Workers + HonoJS)

Set up endpoints for bill uploads, bill data retrieval, and notifications.

Securely store bill data and user info (no peeking, promise).

### AI Integration (Azure OpenAI)

Send uploaded bill scans to Azure OpenAI for OCR and data extraction.
Parse and return structured bill details to the backend.

### Notifications

Implement reminders for upcoming due dates (email, push, or interpretive dance—TBD).

### Testing & Polish

Test with a variety of bill formats (the weirder, the better).
Squash bugs, add polish, and sprinkle in some cosmic charm.

### Stretch Goals

- Multi-language support (for bills from far-off galaxies).
- Analytics dashboard (because who doesn’t love graphs?).
- Integration with payment providers for one-click bill pay.

## TL;DR

Scan, extract, track, and never miss a bill—Billiverse is your AI-powered bill butler in the cloud. 🪐✨
