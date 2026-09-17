# 🤖 Multi-Agent Supply Chain Automation System
**Electro-Tech Representatives Ltd.**

Enterprise-grade Multi-Agent System built with **n8n**, **Ollama/OpenAI**, **Pinecone Vector Store**, and **Google Sheets** for automating supply chain workflows from RFQ to Invoice.

---

## 📌 Architecture & Key Features
- **Snake Architecture**: Synchronous, one-way flow with sub-workflows for each agent.
- **Dynamic Routing**: Orchestrator determines pipeline execution based on order type (RFQ, PO, RFI, NPI).
- **Human-in-the-Loop (HITL)**: Email approval flow for orders exceeding credit limits or high value ($30K+).
- **Multi-Currency Support**: USD supplier purchase orders & ILS customer invoices with real-time FX conversion.
- **RAG Technical Search**: Pinecone Vector Store integration for datasheet and component lookup.

---

## 👥 Agents Included
1. **Orchestrator Agent**: Pipeline determination & request routing.
2. **Technical Agent**: Part validation & vector store RAG lookup.
3. **Pricing Agent**: Dynamic price calculations, markups, and currency conversion.
4. **CRM Agent**: Quotation creation, credit checks, and customer notifications.
5. **Procurement Agent**: Supplier purchase order issuance in USD.
6. **Logistics Agent**: Warehouse receipt confirmation and inventory updates.
7. **Finance Agent**: Commercial ILS tax invoice generation and payment term validation.
8. **Admin Agent**: Audit logging and database updates.
9. **HITL Manager**: Executive authorization workflow.

---

## 👤 Author
**Yossi Yetmano**  
*AI Workforce Architect Certification — Capstone Project (2026)*
