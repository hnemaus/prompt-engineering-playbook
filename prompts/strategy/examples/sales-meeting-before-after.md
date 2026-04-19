# Example: Sales Meeting Notes → Structured CRM Summary

This example shows how a structured prompt can turn messy meeting notes into a clear CRM entry.

---

# Raw meeting notes (before)

Met with Lars from Nordic Retail.

They are struggling with manual reporting and spreadsheets.

Mentioned they want to automate reporting across stores.

Budget not decided yet but they seemed positive.

Asked about integration with existing systems.

Next step might be demo but need to involve CTO.

---

# Prompt used

ROLLE:
You are a sales operations assistant.

OPPGAVE:
Convert raw meeting notes into a structured CRM entry.

FORMAT:

Company:
Contact:
Key needs:
Buying signals:
Risks:
Next step:

KONTEKST:
The notes may be messy and incomplete.

INPUT:
[MEETING NOTES]

---

# AI Output (after)

Company: Nordic Retail  
Contact: Lars Hansen  

Key needs:
Automation of reporting across multiple retail stores.

Buying signals:
Strong interest in automation solutions. Asked about integrations.

Risks:
Budget not confirmed yet. CTO needs to be involved.

Next step:
Schedule product demo with technical stakeholders.

---

# Why this works

The structured format forces the model to organise information into consistent CRM fields.

This reduces manual work and improves CRM data quality.
