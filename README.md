# Reven Relationship Desk — concept demo

A local, interactive prototype for a client follow-up workflow, prepared as an interview conversation starter. All client names, contacts, teammates, activity, and email addresses are fictional. This is an independent concept, not an official Reven product.

## Run locally

Install [Node.js 20.19+ or 22.12+](https://nodejs.org/), then:

```bash
npm install
npm run dev
```

Open the URL printed by Vite, usually <http://localhost:5173>. To check the production build: `npm run build`.

## Demo path

1. On **Overview**, see overdue and upcoming relationships.
2. Open **Northstar Technologies** to inspect context and change its cadence.
3. Select **Prepare follow-up**, edit the sample draft, then **Mark contacted in demo**. This records a local event; it does **not** send email.
4. Open **Follow-up queue**, **Calendar**, and **Team overview** to show the daily and manager workflows.
5. Use **Settings & integrations → Reset sample data** to restore the initial recording state.

Client notes, cadence changes, added clients, and activity persist in the current browser's local storage. There is no backend, authentication, actual AI generation, mailbox connection, or CRM integration. The sample draft uses a deterministic template and sample notes. The team view includes illustrative aggregate data for teammates. The UI labels these limits so the concept can be shown honestly.
