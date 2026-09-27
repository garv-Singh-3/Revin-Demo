# Revin Relationship Desk — concept demo

A local, interactive prototype for a client follow-up workflow, prepared as an interview conversation starter. All client names, contacts, teammates, activity, and email addresses are fictional. This is an independent concept, not an official Revin product.

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
4. Open **Email bot demo** for the six-scene, animated inbox workflow: overdue detection, employee reminder, suggested draft, SEND/edit reply, simulated mailbox send, and CRM update.
5. In **Settings & integrations**, switch the sample mailbox between Outlook and Gmail and adjust reminder, draft, and reply-approval toggles.
6. Open **Follow-up queue**, **Calendar**, and **Team overview** for the optional dashboard views. Use **Settings & integrations → Reset sample clients** to restore the initial recording state.

Client notes, cadence changes, added clients, activity, and assistant settings persist in the current browser's local storage. There is no backend, authentication, actual AI generation, mailbox connection, email delivery, reply processing, or CRM integration. The sample draft uses a deterministic template and sample notes. The inbox scenes and teammate totals are illustrative. The prototype labels these limits so the concept can be shown honestly.
