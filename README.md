# Personalized Tour Inquiry Response using AI – n8n Workflow

This automation handles personalized responses for travel inquiries using AI. It collects form submissions from Tally, generates a tailored email reply using OpenAI, drafts it in Gmail, logs the data in Google Sheets, and notifies your team — all automatically.

---

## Purpose

- Save time replying to inquiries manually
- Ensure fast, friendly, and human-like responses
- Centralize all inquiry data in one live CRM (Google Sheets)
- Empower teams with visibility and follow-up alerts

---

## Workflow Overview

1. **Webhook (Tally Form)** – collects traveler details like destination, dates, and preferences.
2. **Google Sheets (Append)** – logs inquiry into the “Tour Inquiry CRM” sheet.
3. **OpenAI Node** – generates a warm, personalized draft email.
4. **Validation (Switch/If)** – checks for email validity and OpenAI success.
5. **Retry Logic** – re-attempts email generation if OpenAI fails.
6. **Gmail Node** – saves the draft email to your Gmail account.
7. **Google Sheets (Update)** – records the draft in the sheet.
8. **Team Alert (Gmail)** – notifies your team that the response is ready.

---

## Benefits

- Fast customer replies without sounding robotic
- Human is invloved in the loop
- Improved follow-up and conversion visibility
- Clean data pipeline for reporting and CRM syncing
- Ideal for small teams handling high inquiry volume

---

## Tools Used

- [n8n](https://n8n.io/)
- [OpenAI](https://openai.com/)
- [Tally](https://tally.so/)
- [Google Sheets](https://workspace.google.com/)
- [Gmail](https://gmail.com/)

---

## Future Improvements

- Add translation support based on nationality
- Sync with ClickUp or Notion for pipeline follow-up
- Auto-send itinerary PDF after manual approval

---


