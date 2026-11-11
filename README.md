<h1 align="center">Ziad Mohamed</h1>
<p align="center"><b>AI Automation Engineer</b><br>n8n &middot; AI Agents &middot; RAG &middot; WhatsApp Automation</p>

<p align="center">
  <a href="https://linkedin.com/in/ziad-mohamed-832807340"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ziadautomation.ai@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://youtu.be/A774L_G5KpU"><img src="https://img.shields.io/badge/Video-Watch-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Video"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Internships-2ea44f?style=flat" alt="Open to remote internships">
  <img src="https://img.shields.io/badge/Based%20in-Egypt-lightgrey?style=flat" alt="Egypt">
  <img src="https://komarev.com/ghpvc/?username=ziadmohamed-ai&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views">
</p>

---

### About

I build AI agents and n8n workflows that connect language models to WhatsApp, CRMs and databases. My focus is **reliable behavior**: input validation, idempotent writes, fallbacks and clean human handoffs. I keep the AI away from core logic, so a bad model answer can never corrupt data.

Student at Sohag University, Egypt. Building in public and open to remote AI automation internships.

### Featured projects

#### [ClinicOS: WhatsApp AI Receptionist and Appointment Engine](https://github.com/ziadmohamed-ai/ClinicOS-WhatsApp-AI-Engine)
Arabic-first WhatsApp receptionist for clinics. Understands Egyptian and Gulf dialects and voice notes. The AI talks, the database decides: bookings, reschedules and confirmations run in 32 Postgres functions with conflict-proof slots, HMAC-verified webhooks and instant human handoff for emergencies. 30-node n8n workflow, full SQL and walkthrough video included.
`n8n` `Supabase` `PostgreSQL` `OpenAI` `WhatsApp Cloud API` `HMAC` `Outbox pattern`

#### [Real Estate WhatsApp Lead Automation](https://github.com/ziadmohamed-ai/real-estate-whatsapp-lead-automation) ([watch the video](https://youtu.be/A774L_G5KpU))
Every WhatsApp message becomes a validated database record, with an AI agent handling the conversation. Saving, duplicate checks and timestamps run on fixed rules, not on the model.
`n8n` `WhatsApp Business Cloud API` `Supabase` `AI Agent`

### Other projects

- **AI Lead Qualification and CRM Automation**: webhook intake, AI lead scoring, HubSpot sync, Slack routing, duplicate handling. `n8n` `HubSpot` `Slack`
- **WhatsApp RAG Customer Support Agent**: answers from a Supabase pgvector knowledge base, with conversation memory and human handoff. `n8n` `OpenAI` `pgvector`
- **WhatsApp Appointment Automation**: checks free Google Calendar slots, separates availability from booking, sends confirmations. `n8n` `Google Calendar`
- **AI Lead Generation Automation**: lead collection, enrichment and AI-assisted qualification with status tracking. `n8n` `APIs`

### How I build

- **Deterministic core, AI at the edges.** Validation, deduplication, state changes and timestamps are rule-based. The model only understands and replies.
- **Idempotency first.** The same message or event is never processed twice.
- **Fail safe.** Uncertain or sensitive cases go to a person instead of a guess.
- **Test the failure cases.** Edge cases and attempts to make the agent invent answers.

### Tech stack

<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp">
  <img src="https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white" alt="HubSpot">
  <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white" alt="Slack">
  <img src="https://img.shields.io/badge/Google%20Calendar-4285F4?style=flat&logo=googlecalendar&logoColor=white" alt="Google Calendar">
</p>

| | |
|---|---|
| **Automation** | n8n, Webhooks, Error Handling, Data Validation |
| **AI** | AI Agents, LLMs, Prompt Engineering, RAG, Embeddings, Speech-to-text |
| **Data** | Supabase, PostgreSQL, SQL, pgvector, Row-Level Security |
| **Integrations** | WhatsApp Business Cloud API, HubSpot, Slack, Telegram, Google Calendar, REST APIs |
| **Languages** | JavaScript, Python |

### Certifications

- Agentic AI Engineering (Code and No-Code), Karim Nabil
- AI Sales Automation Using n8n, Udemy

### Contact

Open to AI automation internships (remote or Egypt).
[LinkedIn](https://linkedin.com/in/ziad-mohamed-832807340) &middot; [ziadautomation.ai@gmail.com](mailto:ziadautomation.ai@gmail.com)
