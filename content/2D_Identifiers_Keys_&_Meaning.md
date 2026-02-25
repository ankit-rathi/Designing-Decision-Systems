## **D. Identifiers, Keys & Meaning**

**Why:** Without consistent identifiers, you cannot track entities over time or across systems.

**What:** Identifiers are **unique keys** linking observations to entities.

**How:** Use stable IDs to unify data. Example: Customer IDs connecting transactions across multiple systems ensures coherent longitudinal analysis.

---

From first principles, analysis depends on continuity. If you cannot reliably determine whether two records refer to the same underlying entity, you cannot measure change, behavior, or causality. Identity is the backbone of longitudinal reasoning.

An **identifier** is a stable, unique key that links observations to a specific entity. It answers a simple but foundational question: “Is this the same thing as before?” Without that anchor, data fragments into disconnected snapshots.

Consider a customer making purchases across a mobile app, website, and physical store. If each system generates its own internal reference without a shared customer ID, you create three partial identities. The result: inflated customer counts, distorted lifetime value calculations, and flawed churn analysis. The absence of a stable key destroys analytical coherence.

Identifiers enable **state tracking over time**. Suppose you want to understand credit risk progression. You need to connect payment events month after month to the same loan account. Without a consistent loan ID, you cannot observe transitions from current → delinquent → default. You lose temporal causality.

Identifiers also enable **cross-system integration**. A marketing platform may track campaign exposure. A transaction system tracks purchases. A support system logs complaints. Only through a shared customer ID can you analyze whether campaign exposure increases purchases or triggers complaints. Without linkage, insight remains siloed.

The design of identifiers matters. They must be:

* **Unique** (no duplication),
* **Stable** (do not change arbitrarily),
* **Consistent** across systems.

If identifiers change — for example, regenerating IDs when a customer updates their email — historical continuity breaks. Trend analysis becomes unreliable.

There is also a deeper principle: identifiers create meaning through reference. A number like “78421” is meaningless unless consistently tied to an entity. The key does not carry intelligence; it carries *continuity*.

Poor identity management leads to double-counting revenue, misallocating marketing budgets, and misunderstanding risk exposure. At scale, identity errors compound into strategic distortion.

Strong decision systems treat identifiers as infrastructure, not metadata. They invest in master data management, reconciliation rules, and governance. Because without stable identity, you cannot connect events to entities, cannot trace states over time, and cannot convert data into causal understanding.
